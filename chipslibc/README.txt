ChipDev Standard C Library
--------------------------

The Purpose of the Standard C Library is to build a library for the ChipDev C Compiler that would support many programming standards and many extensions to the C programming language.

Standards:
These are the standards we are aiming to support.
ISO 8957:1996 (HEB96)
ISO/IEC 2022:1994 (CHARCODE94)
ISO/IEC 23360-2:2006 (LSB06)
ISO/IEC 9593-4:1991 (PHIGS91)
ISO/IEC 9899:1999 (C99)
ISO/IEC 9899:2011 (C11)
ISO/IEC/IEEE 8802-3:2021 (LAN/MAN21)
ISO/IEC/IEEE 9945:2009 (POSIX09)

Keywords (Defined in ../chipslibc/README)

Headers:
These are the files to include for definitions.
aout.h - a.out Support
arabic.h - Support for the Arabic script and language
assert.h
bin/coff.h - Extra COFF Support
bin/elf.h
bin/xcoff.h - Extra XCOFF Support
bits/lang.h - Hidden Language Support
chinese.h
codepg.h - Codepages
coff.h
complex.h
ecoff.h - ECOFF Support
elf.h - ELF Support
elfex.h - ELF Extensions
english.h - Support for the English language
fareast.h - Far East Script Support
ftp.h - FTP Support
greek.h
hebrew.h - Support for the Hebrew language and script
http.h - HTTP Support
https.h - HTTPS Support
latin1.h - Support for Latin Script and language
latin2.h - Nonstandard Latin Symbols
latin3.h - More Nonstandard Latin Symbols
libgen.h
limits.h
locale.h
net/arpa.h
net/ftp.h - Basic FTP Support
net/https.h - Basic HTTPS Support
os/bsd.h - BSD API ported to each chip
os/dos.h - DOS API ported to each chip
os/linux.h - Linux API ported to each chip
os/os2.h - OS/2 API ported to each chip
os/posix.h - POSIX API ported to each chip
os/unix.h - UNIX API ported to each chip
os/win32.h - Win32 API ported to each chip
os/wince.h - Windows CE API ported to each chip
signal.h
stdbool.h
stddef.h
stdint.h
stdio.h
stdlang.h
string.h
sys/lang.h
sys/types.h
uchar.h - Unicode Characters
wchar.h - Wide-Byte Characters
xcoff.h

Functions:
These are the functions in the library.
elf_exec (elf.h) - Execute ELF Binary
exit (stdlib.h) - Normal Process Termination
load_elf (elf.h) - Load ELF Binary
printf (stdio.h) - Prints formastted output to stdout, a file stream, or a buffer
putc (stdio.h) - Output Characters and Strings
strlen (string.h) - Returns the length of a given string
uselocale (locale.h) - Set/Get locale for calling thread

Macros:
These are the macros in the library.
bool (stdbool.h) - Convenience Macro that expands to _Bool
CHAR_BIT (limits.h) - Number of bits in a byte
LC_CTYPE (locale.h) - Locale Category for the setlocale function
NULL (stddef.h) - Null pointer constant

Typedefs:
These are the types defined in the library.
gid_t (sys/types.h) - Used for Group IDs
intptr_t (stdint.h) - Integer Type for Pointers
size_t (stddef.h; sys/types.h) - Used for Sizes of Objects
uintptr_t (stdint.h) - Unsigned Integer Type for Pointers

Structs:
These are the structures defined in the library.
lconv (locale.h) - Formatting details that are returned by localeconv
-> mon_grouping - A string whose elements indicate the sizes of digit groups
