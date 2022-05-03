# task1_os
In this task we have blinked the onboard led on the 2nd pin of esp32 and an led connected to pin 19 of the esp32. We have built our own workspace by:
1)Creating the CMakeLists.txt file which includes our project name and the path for the esp idf tools.
2)Next we create the main subdirectory which consists of the main.c file and the CMakeLists.txt file. These files are used to run the functions which
are created in the components.We pin the tasks to the cores in main.c.
3)Next we create a sub directory for the components, under which the core0.c file is the main file which consists of the code to be run. The CMakelists.txt
 file consists of adding drivers.
4)We also create a sub directory called include to add the functions to be run. We create a header file in .cthis sub directory, which is later called in main
