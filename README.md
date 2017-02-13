Q1) Write a java code with the class named ‘acad’ and a method ‘main’.
Hardcode the program with two integers and print the sum of those two.


import java.util.*;
public class acad {

public static void main(String[] args) {
int a=5;
int b=4;
int c;
c=a+b;
System.out.println(c);

}

}



Q2) Rewrite the above code, where, inputs are provided by the user at
runtime and the output is printed.


import java.util.*;
public class acad {

public static void main(String[] args) {
Scanner ss = new Scanner(System.in);
int a=ss.nextInt();
int b=ss.nextInt();
int c;
c=a+b;
System.out.println(c);

ss.close();
}

}



Q3) Write a program with method name sum() that accepts two parameters
from user and print the sum two numbers. Output format should be as.


import java.util.*;
public class acad {

public static void main(String[] args) {
sum();
}

static void sum()
{
Scanner ss = new Scanner(System.in);
int a=ss.nextInt();
int b=ss.nextInt();
int c;
c=a+b;
System.out.println(c);

ss.close();

}
}
