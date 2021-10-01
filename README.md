This project is based on the concept of 'MapReduce', following process spawning, directory traversal, file I/O operations, pipes, and redirection.

Purpose:
  the purpose of this project is to take a multi-level hierarchy directory and partition
  them into M number of mappers. each mapper text file is then read through phase
  two to get a word count of the first letter in each word. Phase 3 then puts the
  total number letter count into one file. the last phase will then put it into
  the correct file output.

Compile:
  compile by typing gcc main.c phase1.c phase2.c phase3.c phase4.c -o main, then run by typing ./main 
  
Run:
  ./main folderName #mappers
  
Assumptions:
Number of masters=1, 0<Number of mappers<=32 and Number of reducers=1.
File count>=number of mappers except for the case of empty folder.
There will not be any space in the folder or file names.
