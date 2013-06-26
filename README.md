PhpDbDiff
=========

Simple tool for compare two databases schemas.
Based on PhpDbDiff code from 

Sandino Nunez <sandinosaso@gmail.com>
=>Added the posibililty of generate sql to perform a transformation between an
  old database schema and a new one. The compare tools ramains the same.
  

===

### To build:

Prerequisites :

    * Apache server and Mysql database
    * PHP >= 5

Put the files in your "www" folder

### To run the tests:

Unix/Macintosh:

    make test

Windows:

    vcbuild.bat test

### To build the documentation:

    make doc

### To read the documentation:

    man doc/DbDiff

Resources for Newcomers
---
  - [The Wiki](https://github.com/)
