FOS( Fast Operating System )
==========

It's a open soruce project about code RTOS(Real Time Operating Systems), named FOS, alias Chinese Operating System, not COPY OTHER SYSTEM, based on OpenRISC.

Now it will be complete step by step, I hope more and more people will be to make it perfecter.

---------------------------------------------------------------------------

To build the FOS, tools need: scons and or1ksim.

CD to the RTOS directory and run:
'scons'

This will produce two execution files, one is for or1ksim, the other is for real openrisc chip.

To run the FOS for or1ksim, run the shell script:
'./start_or1ksim.sh'

---------------------------------------------------------------------------

SOURCE TREE:

 * kernel                   :      Core kernel sources
 * app                      :      User application sources
 * cpu                      :      CPU architecture ports
 * libc                     :      C function library.
 * middleware               :      The component for FOS
 * SConstruct and config.py :      Compile tools
 * start_or1ksim.sh         :      Run the system in the or1ksim

Contributions:
==============
This software was written by Shanjin Yang. License: GPL. 
Any question please contact me by <sjyangv0@qq.com>.
