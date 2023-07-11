# CookieCat

CookieCat is a simple Pascal chess program by Steven Edwards. In this repository you can find a retouched version of the program.

You can find more informations about the program and download of the original source code here:
https://www.chessprogramming.org/CookieCat

## Compilation

This program was developed using the Free Pascal compiler, version 2.4.4.  For more information
about Free Pascal, see the www.freepascal.org web site.  To download a free copy of the compiler,
see the www.freepascal.org/download.var web page.

The author gratefully acknowleges the work of all those who have contributed to the Free Pascal
project.

To install Free Pascal on Linux, try: sudo apt-get install fpc

To compile this program for a 32 bit machine, try: fpc -O3 CookieCat.pas

To compile this program for a 64 bit Intel/AMD machine, try: ppcx64 -O3 CookieCat.pas

## Credits

This program is an original work and not a clone; no source was copied from any other program.
However, there are some major ideas seen here which were in use long before this program was
written.

The split/merge sort used in this program was discovered by John von Neumann in 1945.

Claude Shannon wrote about the idea of a chess program in 1949.

Alan Turing wrote the first chess program, the manually executed Turochamp, in 1950.

The use of a bitboard representation for game pieces was first well documented by Arthur Samuel
in the late 1950s as part of his checkers program (see: en.wikipedia.org/wiki/Arthur_Samuel).
Samuel also wrote of many other game programming techniques used in his checker player which are
now seen in nearly all chess playing programs.

Alex Bernstein implemented the first machine executable chess program in 1957.

John McCarthy, the author of the Lisp programming language, developed Lisp predicate functions
in 1958 in part to handle chess programming conditionals.

The use of a bitboard representation and a bitboard database for chess was developed by Larry
Atkin and David Slate, authors of the Northwestern program Chess 4.x and also by the authors of
the Soviet program Kaissa.  This work took place from the late 1960s to the mid 1970s.

In 1970, Albert Zobrist developed a hashing scheme used for incremental updating of a chess
position hash signature.

The chess data interchange standards (EPD, FEN, PGN, and SAN) were developed by Steven Edwards
with the help of the Usenet community and were first published in 1994.

Several people have contributed their time and skill helping with testing.  Their assistance
is sincerely appreciated.

-- Dann Corbit
-- Roland Chastain (for fixing a memory leak)
