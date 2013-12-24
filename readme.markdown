This is a test package for Babel's test suite.

**PackageA**

This package has 4 different versions.

Version 0.2 contains two procs
one in packagea.nim (``test`` which is the same as ``+``) and one in packagea/test.nim
 (``test2`` which is the same as ``*``). 

Version 0.5 removes packagea/test.nim (through the use of skipDir) but adds a
``onlyIn04`` to packagea.nim.

The other versions are irrelevant and are caused by my excessive tagging.

HEAD is currently at version 0.6.0 as a test for issue nimrod-code/babel#22.