

Example
-------

Arduino
*******

For example:

.. code-block:: python
   
   from roboboards import Arduino # UNO
  
   mcb = Arduino()
  
   mcb.whoami()
   Arduino v0.01.12c 

   mcb.clock.uptime()
   00:02:19

   mcb.listAllPins()
     0 -----
     1 -----
     2 -----
     3 -----
     4 -----
     5 -----
     6 -----
     7 -----
     8 -----
     9 -----
     10 -----
     11 -----
     12 -----
     13 -----
   
     0 -----
     1 -----
     2 -----
     3 -----
     4 -----
     5 -----

   mcb.setAnalogPin(2)

   mcb.listPins()
   2 ANALOG : INPUT - 

   mcb.listAllPins()
     0 -----
     1 -----
     2 -----
     3 -----
     4 -----
     5 -----
     6 -----
     7 -----
     8 -----
     9 -----
     10 -----
     11 -----
     12 -----
     13 -----
   
     0 -----
     1 -----
     2 ANALOG : INPUT - 
     3 -----
     4 -----
     5 -----
   




