# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
Given a month number (1 to 12), print which quarter of the year it belongs to:

Months 1,2,3 → "First Quarter"

Months 4,5,6 → "Second Quarter"

Months 7,8,9 → "Third Quarter"

Months 10,11,12 → "Fourth Quarter"
If the number is not in 1-12, print "Invalid Month".

Write a java program to get the month from user and and display appropriate output for the given input.

For example:

Input	Result
2
First Quarter

## AIM:


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	





## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by:BHAVATHARANI S 
RegisterNumber: 212223230032 
*/
import java.util.Scanner;
public class Main{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int month = sc.nextInt();
        
        if(month >= 1 && month <= 3){
            System.out.println("First Quarter");
        }
        else if(month>=4&&month<=6)   { 
            System.out.println("Second Quarter");
        }
        else if(month>=7&&month<=9){
            System.out.println("Third Quarter");
        }
        else if(month>=10&&month<=12){
            System.out.println("Fourth Quarter");
        }
        else{
            System.out.println("Invalid Month");
        }
        sc.close();
    }
}
```


## OUTPUT:
<img width="1239" height="274" alt="image" src="https://github.com/user-attachments/assets/86104a7a-fd7a-4d44-88b4-089c38ed25c6" />



## RESULT:

