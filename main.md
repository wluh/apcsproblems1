## classes

1. Attributes are typically ______ variables.

Private, Public, Static, Immutable

2. GPS Coordinates
Write a *GPSLoc* class to represent a GPS location using the world's coordinate system.

Latitude is a number between -90 and 90
Longitude is a number between -180 and 180

Write 5 methods:

```
GetLat()
GetLong()
SetLat(double lat): If the input is invalid, set it to 0.
SetLong(double long): If the input is invalid, set it to 0.
DistanceTo(GPSLoc location)
```

## regular for loops

How many times does line 2 get repeated?

```
for (int x = 0; x < 99; x += 2) {
  System.out.println("Loop has iterated!");
}
```

What is the value of x when the loop terminates?

```
for (int x = 0; x < 99; x += 2) {
  System.out.println("Loop has iterated!");
}
```

## nested loops

How many times does line 3 get repeated?

```
for (int x = 0; x < 100; x += 2) {
  for (int y = 0; y < 1; y += 1) {
    System.out.println("Loop has iterated!");
  }
}
```

How many times does line 3 get repeated?

```
for (int x = 0; x < 100; x += 2) {
  for (int y = 0; y < 5; y += 1) {
    System.out.println("Loop has iterated!");
  }
}
```

How many times does line 3 get repeated?

What is the value of the variable x when the loop is terminated?

What is the value of the variable y when the loop is terminated?

```
for (int x = 1; x < 33; x *= 2) {
  for (int y = 0; y < 5; y += 1) {
    System.out.println("Loop has iterated!");
  }
}
```

## strings

What is the output of the following code?

```
String s1 = "hello";
String s2 = "goodbye";

System.out.println(s2.substring(3).join(s1));
```

What is the output of the following code?

```
String s1 = "hello";
String s2 = "goodbye";

System.out.println(s2.substring(3).join(s1.charAt(2)));
```

## scope

1. What is the output of the following code?

```
String s1 = "hello";
String s2 = "goodbye";
String s3 = s2;

s1 = s3;

System.out.println(s1);
```

2. Can a method be private?

3. In what case could we use a private method?

4. In what case could we use a static variable?

5. Is there an error in the following code? If so, propose a solution that will let the code compile and run.

```
public static void main(String args[]){
  int y = 0;
  for (int x = 0; x < 5; x += 1) {
    System.out.println(addNumbers(x,y));
    y += 1;
  }
}

public int addNumbers(int a, int b) {
  return (x + y);
}
```


## if statements

What is wrong with the following code?

```
else if (x > 0 && x <= 3) {
...
}
else if (x > 3 && x <= 6) {
...
}
else {
...
}
```

Rewrite the code with a solution that will fix the issue.


Write a function that returns true is an integer is even and odd if a number is odd.
```
public boolean parity(int x) {
...
}
```

## 1d arrays

What is the output of the following code?

```
int[] intArr = new int[3];
intArr[0] = 2;
intArr[1] = 4;
intArr[2] = 6;
intArr[3] = 7;
System.out.println(intArr[0]);
```


What is the output of the following code?

```
int[] intArr = new int[3];
System.out.println(intArr[2]);
```

Write a function that iterates through an integer array and prints out the value of each integer inside.

```
public void printIntegerArray(int[] array) {
...
}
```

## 2d arrays

How many cells are inside this array?

```
int[] myArray = new int[10][10];
```

Write a block of code that iterates through a 2d integer array and prints out the value of each integer inside.

```
public void print2DIntegerArray(int[][] array) {
...
}
```
