The main idea of Scannerc is to rewrite the source code of a C or C++ so that the resulting code contains the safe version of the old vulnerable funntions .which may contain a buffer overflow sercurity  problem .If rewriting is not possible, due to some reasons, a warning is issued along with a hint to solve the problem if its possible .
How to run 
It's a simple exe program for scanning source code for security problems. 

C:\> scanner-windows.exe  scanner-windows.exe scanner-windows.exe scanner-windows.exe


Our Scanner Currently works detecting these following functions:

1.STRCPY  2.STRCAT 3.SPRINTF 4.GETS 5.VSPRINTF 6.BCOPY 7.SCANF 8.GETOPT 9.GETPASS 10.STRECPY 11.STREADD 12.STRCCPY 13.STRTRNS 14.STRPCPY 15.WCSCPY 16.WCSCAT 17.GETWD 18.REALPATH 19.MEMCPY 20.MEMCCPY 21.MEMCHR 22.MEMMOVE 23.MEMSET
The Red marked functions will be replaced as safer version in the output file but as our scanner source code is customizable we can add more functions in the re-write format. Rest of the functions the scanner will show the risk warnings. Risk-warnings are divided into three categories based on the IBM coding alert document. Here is the link
http://www.blogjava.net/woxingwosu/archive/2007/07/10/129296.html

The Innovationtion Research Group,
The School of Computer Science,
The Northwestern Polytechnical University.
