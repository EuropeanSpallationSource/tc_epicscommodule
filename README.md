# tc_epicscommodule

This is a TwinCAT projed (hence the tc_) to provide a  
TCP/IP server on the TwinCAT PLC talking ASCII.  
It has been used with EPICS (hence the name).  

What is EPICS ? See  
https://epics-controls.org  
However, the communication, as seen from the PLC, is completely  
independent of EPICS (but we couldn't find a better name).  

This module may be usable if you want to use telnet to explore  
functions inside the PLC.

Or write ASCII based applications in python, c++, java, rust, whatever.  

Note that interfacing a PLC today can be done in different ways:
  python has pyads,  
  c++ has the ADS library from Beckhoff,  
  rust has developped bindings.  

So this module is kind of feature complete.  
If you want to use it, see  
POUs/README.TcPOU
