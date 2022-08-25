# dcref
Mark Ogden has restored the source code of the cross-reference tool from the HiTech C compiler v3.09.

Now all HiTech C compiler v3.09 programs have C source code.

Мodified master files to reflect the addition to support compilation on UZI along with other changes as noted below

All builds use xgets, as gets is dangerous and is removed in current C.

Мodified the use of getargs to be gated by USE_GETARGS, with a note explaining it. CPM does include it.

The readme.md file is divided into two parts -  readme.md and build.md, which now includes windows build and reflects the getargs changes.

To compile an executable program cref3 with gcc, run the program

        gcc -O2 -o cref3 cref.c getargs.c fname.c

for CP/M operating system

        zc3 -o -CPM cref.c

for operating system UZI-180

        zc3 -o cref.c

Source code posted with permission from Mark Ogden.
 
Andrey Nikitin 
 25-08-2022

