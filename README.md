
## BUILD and RUN ##

TASK1:
	For build : 
	make -f Makefile_2
	make -f Makefile_3
	
	If you want to build the project using Makefile_1, you must first build the .o files using previos command, then run this command:
	
	make -f Makefile_3
	
	For execure :
	./program
	
TASK2: 
	For build :
	make -f Makefile METHOD=include
	
	or if u want use "make -f" method follow this command:
	make -f Makefile METHOD=include
	
	For execure :
	./program
	
## Clean ##

TASK1
	make -f Makefile_2 clean
	make -f Makefile_3 clean

TASK2
	make -f Makefile clean
	
