# HAM_VNA_Lazarus
Original code from: https://github.com/VE3NEA/HamVNA
VE3NEA HamVNA with my recent modifications to opening of S11 files, display of RLC equivalent circuit etc. 
Some additions: export SPICE model to clipboard on right click (popup menu) on RLC picture,
export of chart or RLC to clipboard on double-click etc.
This copy is compiled with Lazarus 3.0.4, hence inflated exe size. 
Compilation to 32 bit possible as long as original LAPACK wrap is used in attached DLL files. 
Work continues on 64 bit, needs latest Lapack wrap 587.dll. 
My thanks to Alex VE3NEA for  for indicating me original source 
https://www.netlib.org/toms-2014-06-10/587 and some more helpful advice.
Intended to work in the future with NanoVNA and direct USB access.
Tested with Win10 and compatibility settings are illustrated in PNG file: Run as admin and High DPI, System (Enhanced).
73 de Tomasz Mi6HQA
