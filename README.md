# Mod5-A1

* @author Muhammad Ali
* @date 06/08/2024
* @module 5
* @assignment 01
* @project 05 - Planning and Executing a Maintenance Task
* @version 2.0

The Plan:
---------------------
1) Replace LinkedList with Stack. 
2) Modify the add operation, replace the list.add(number) with stack.push(number).
3) Modify the sort operation: Stacks are not meant to be sorted like Lists, insert elements in their correct order right from the start. However, as this is a maintenance task, reuse as much code as possible, convert the Stack back to a List, sort the List, and then convert it back to a Stack.
4) Modify the print operation: replace the direct print statement with a while loop that pops elements from the stack and prints them until the stack is empty.

Class reuse examples:
---------------------
1) Java Collections Framework: Stack<Integer> stack = new Stack<>();
2) Scanner class: Scanner scanner = new Scanner(System.in);
3) Exception handling: try { .... }
4) Sorting functionality: Collections.sort(list, Collections.reverseOrder());
5) Printing functionality: System.out.println("Sorted list:"); while {....}


Two folders included:
---------------------
_SortedIntegers - Compiled - Javadoc Included: this folder includes the compiled version with the javadoc files

SortedIntegers: This folder only includes the program Java files, which must be compiled first, and javadoc needs to be generated. I have tested Using the following command in the next section.


Instructions - to be used from inside the folder 'SortedIntegers' or the other folder if only running the program:
----------------------------
To create the javadoc files from the command:
javadoc edu/merrimack/sorting/SortedIntegers.java

To compile the Java file, use the command:
javac edu/merrimack/sorting/SortedIntegers.java

A new file, SortedIntegers.class, will be created in the same directory as the Java file.

To run the program, use the command:
java edu.merrimack.sorting.SortedIntegers
