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


## Core Libs
- `java.lang`: fundamental to core math, boolean and byte and core java.
- `java.util`: scanning, formatter, data manipulation (random)
- `java.net`: infra for networking.


## Generate random number
```
import java.util.Random;

Random rand = new Random();
int randInt = rand.nextInt();
int randInt0_9 = rand.nextInt(10); // random from 0 to 9 (including 9)
```

## OOP
- Encapsulation: hide data and expose it to the outside via a method.
- Inheritance: to minimize duplicate codes. Could be tightly coupled between subclass and superclass, harder to debug
- Polymorphism: runtime (method override) and compile time (method overloading)


## Functional programing
- Objects are immutalble

```
Predicate isOdd = n -> n % 2 != 0;
isOdd.test(5);

Answerable phone = () -> 'Hello';
phone.answer();
```
