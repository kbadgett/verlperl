# verlperl

1) embedded perl interpreter:

Using System Verilog DPI, we embed a perl interpreter so we can easily use perl during verilog runtime. This is useful for glue code, stimulus generation, intelligent logfile output.
This project includes a library of useful routines that should grow with use.

2) Verilog parser:(qvp.pm) Based on the Rough Verilog Parser API, (http://www.burbleland.com/v2html/rvp.html) this compact and extensible parser has been 
used to parse large, complex designs and make structural synthesis tool, structural test bench creation and more... 
It should be better with use. One future extension will be to create a signal tracer.
