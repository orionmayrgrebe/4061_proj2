Purpose:
  the Purpose of this project is to take a multi-level hierarchy directory and partition
  them into M number of mappers. each mapper text file is then read through phase
  two to get a word count of the first letter in each word. Phase 3 then puts the
  total number letter count into one file. the last phase will then put it into
  the correct file output.

Compile:
  compile by typing gcc main.c phase1.c phase2.c phase3.c phase4.c -o main,
  or by whatever makefile.

Assumptions:
  testcases are in src
