# CBT291
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 291 is from Rick Hevener of the University of South       *   FILE 291
//*           Carolina, and contains a program to measure CPU       *   FILE 291
//*           instruction execution speed.  This program is         *   FILE 291
//*           supposed to be a bit better than others of its        *   FILE 291
//*           type (I think).  Included in this file, is an         *   FILE 291
//*           article from Technical Support magazine which         *   FILE 291
//*           describes how this program works, and what kind       *   FILE 291
//*           of results you can obtain, using it.                  *   FILE 291
//*                                                                 *   FILE 291
//*     The program in TIMINGSP may be used to test timings of      *   FILE 291
//*     a large number of instructions on mainframe IBM or          *   FILE 291
//*     plug-compatible computers.  The method involves             *   FILE 291
//*     cycling through a loop 25,000 times with 11                 *   FILE 291
//*     instructions per cycle; the overhead for the loop is        *   FILE 291
//*     subtracted.  One may easily modify the above numeric        *   FILE 291
//*     parameters.  The only macros required are in                *   FILE 291
//*     SYS1.MACLIB.  Execution time for the program is             *   FILE 291
//*     approx. 0.5 sec. on the University of South Carolina's      *   FILE 291
//*     2066-0X2 machine.                                           *   FILE 291
//*                                                                 *   FILE 291
//*     The original program is in member TIMINGSO.  It             *   FILE 291
//*     employed 50,000 cycles per loop with only one               *   FILE 291
//*     instruction per cycle.  That program and its results        *   FILE 291
//*     are described in the following article, which is            *   FILE 291
//*     reproduced here in member $ARTICLE:                         *   FILE 291
//*                                                                 *   FILE 291
//*     Richard N. Hevener, "Large System Instruction Timings,"     *   FILE 291
//*     "Technical Support," Vol. 5, No. 8, pp. 14-18, August,      *   FILE 291
//*     1997.                                                       *   FILE 291
//*                                                                 *   FILE 291
//*     In Sep., 1999, Jim Melnyk of Great-West Life sent me an     *   FILE 291
//*     e-mail inquiring about some peculiar results he had         *   FILE 291
//*     obtained using the original program.  He had gotten         *   FILE 291
//*     negative times for certain instructions on a 9672-RC6.      *   FILE 291
//*     After several attempts, I was able to modify the            *   FILE 291
//*     program to achieve reasonable timings on both that          *   FILE 291
//*     machine and a 9672-R55 that Jim later discovered also       *   FILE 291
//*     produced spurious results.  He also tested on a             *   FILE 291
//*     9672-R24, obtaining output consistent with the original     *   FILE 291
//*     program, as I did on U.S.C.'s 9672-R53.  I would like       *   FILE 291
//*     to acknowledge Jim's assistance in testing various          *   FILE 291
//*     versions of the program on his three machines.  I would     *   FILE 291
//*     also like to thank him for suggesting that I employ a       *   FILE 291
//*     loop macro to facilitate changes.                           *   FILE 291
//*                                                                 *   FILE 291
//*     In Aug., 2002, Charlie Hottel of the Washington, D.C.,      *   FILE 291
//*     area raised some questions about the rather complicated     *   FILE 291
//*     computational shifting in the program.  Thanks to           *   FILE 291
//*     Charlie for suggesting a revision (and slight               *   FILE 291
//*     simplification) to prevent a possible 0C9.                  *   FILE 291
//*                                                                 *   FILE 291
//*     My contact information may be found near the beginning      *   FILE 291
//*     of TIMINGSP.                                                *   FILE 291
//*                                                                 *   FILE 291
//*     Rick Hevener (retired, formerly of University of South      *   FILE 291
//*     Carolina) Columbia, S.C.  2005-04-27                        *   FILE 291
//*                                                                 *   FILE 291
```
