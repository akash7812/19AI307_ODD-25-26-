# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
Lovely enters a mystical Power Chamber with 10 doors.
Behind each door is a magic symbol that changes her power in a unique way using compound assignment operators.

She starts with an initial power value, and here's what happens at each door:

Door	Operation	Description

1	+=5	Adds 5 to the power

2	-=3	Subtracts 3

3	*=2	Multiplies power by 2

4	/=4	Divides power by 4

5	%=3	Power mod 3

6	&=7	Bitwise AND with 7

7	^=4	Bitwise XOR with 4

8	<<=1	Left shift by 1

9	>>=1	Right shift by 1
 
Input Format
One integer (initial power)

Output Format
Print the result after each door in this format:

Initial Power = <value>
After Door 1 (+= 5): <value>
After Door 2 (-= 3): <value>
...
After Door 10 (>>= 1): <value>
Final Power = <value>

For example:

Input	Result
10
Initial Power = 10

After Door 1 (+= 5): 15

After Door 2 (-= 3): 12

After Door 3 (*= 2): 24

After Door 4 (/= 4): 6

After Door 5 (%= 3): 0

After Door 6 (|= 2): 2

After Door 7 (&= 7): 2

After Door 8 (^= 4): 6

After Door 9 (<<= 1): 12

After Door 10 (>>= 1): 6

Final Power = 6


## AIM:
To write a Java program that demonstrates the use of compound assignment operators by modifying a power value as it passes through multiple operations.

## ALGORITHM :
1.	Start the program.
2.	Read the initial power value from the user.
3.	Display the initial power.
4.	Apply compound assignment operators step-by-step.
5.	Display the power after each door operation.
6.	Print the final power value.
7.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: AKASH KUMAR M.
RegisterNumber: 212223230010
*/
import java.util.Scanner;
public class main{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        
        int a = sc.nextInt();
        System.out.println("Initial Power = " + a);
        
        a += 5;
        System.out.println("After Door 1 (+= 5): " + a);
        
        a -= 3;
        System.out.println("After Door 2 (-= 3): " + a);
        
        a *= 2;
        System.out.println("After Door 3 (*= 2): " + a);
        
        a /= 4;
        System.out.println("After Door 4 (/= 4): " + a);
        
        a %= 3;
        System.out.println("After Door 5 (%= 3): " + a);
        
        a |= 2;
        System.out.println("After Door 6 (|= 2): " + a);
        
        a &= 7;
        System.out.println("After Door 7 (&= 7): " + a);
        
        a ^= 4;
        System.out.println("After Door 8 (^= 4): " + a);
        
        a <<= 1;
        System.out.println("After Door 9 (<<= 1): " + a);
        
        a >>= 1;
        System.out.println("After Door 10 (>>= 1): " + a);
        System.out.println("Final Power = " + a);
    }
}
```


## OUTPUT:

<img width="687" height="822" alt="image" src="https://github.com/user-attachments/assets/f9c99352-5c47-4fbf-900d-982fe6f64c44" />


## RESULT:

Thus, the Java program demonstrating the use of compound assignment operators was successfully executed and the output was verified.
