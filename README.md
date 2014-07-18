cc65sha256
==========

SHA256 command line utility for 6502 based computers.

Tested to work with Atari 8bit (800XL / 130XE) using SpartaDos and SpartaDOS X (SDX). 
Not tested but should work with MyDOS.
Not tested but should work with other 6502 based computers like:
  VIC20
  Apple IIe
  Apple ][+
  Commodor 64
  Commodor 128

Usage: SHA256 <command> [options]

Commands:
 /S        Generate SHA256 hash
 /T        Run all tests
 /V        Display version info
 /?        Display help info
 
Options:
 /I <file> Input file, defaults to STDIN
 /O <file> Output file, defaults to STDOUT
 /Q        Quiet mode, defaulted to off
 
Program returns 0 if succesful and 1 if failed.

SHA256 "c" functions original written by Christophe Devine and modified by Mark Hoblit to compile under cc65.

Bitcoin donations: 17uKHtsQegbvFpHwMKySVS558m6ZzaVLLk
