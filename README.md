Java_Notes
==========

## jshell
jshell - REPR for java, available in JDK 9

## Read input from stdin using scanner
```
import java.util.Scanner

...

Scanner sc = new Scanner(System.in);

// as string
String inputString = sc.next();

// as double
double inputNumber = sc.nextDouble();
```


## Arrays
New Instance
```
int[] numbers = new int[5];
numbers[0] = 1;
...
numbers[4] = 5;

...
int[] numbers2 = {1,2,3,4,5}
```


## By value or by reference
- Argument is the actual value used for variable passed into the function
- Parameter is the variable to be reference and used in a function
- Java uses call by value, so the original arguments of a function never change.


