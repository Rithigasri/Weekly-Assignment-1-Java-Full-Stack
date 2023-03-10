# Weekly Assignment 1-Java Full Stack
## Name: Rithiga Sri.B 
## Register number:212221230083  
## Department:Artificial Intelligence and Data Science[II Year]
## 1. Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scan=new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int a=scan.nextInt();
        System.out.print("Enter the second number: ");
        int b=scan.nextInt();
        System.out.println("Sum= "+(a+b));
        System.out.println("Subtraction= "+(a-b));
        System.out.println("Multiplication= "+(a*b));
        System.out.println("Division= "+(a/b));

    }
}
```
## Output:
![Q1](https://user-images.githubusercontent.com/93427256/224324180-fae80530-38e8-411c-bc94-849d97c8a926.png)


## 2.Write a Java program to compare two numbers.
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner scan=new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int a=scan.nextInt();
        System.out.print("Enter the second number: ");
        int b=scan.nextInt();
        if(a>b)
            System.out.println("A is greater");
        else if(a<b)
            System.out.println("B is greater");
        else
            System.out.println("A is equal to B");
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93427256/224325197-a52a42cb-02c8-476e-abdc-184499253249.png)


## 3.Write a Java program to convert a string to an integer.
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        System.out.print("Enter the string: ");
        String str=input.nextLine();
        int num=Integer.parseInt(str);
        System.out.println("The number is: "+num);
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93427256/224326614-eef024e3-c40f-4134-978a-447b75332dea.png)


## 4.Java Program to find area of rhombus.
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        System.out.println("Choose the method to find area of Rhombus:\n1.Using diagonals\n2.Using base and height");
        Scanner scan=new Scanner(System.in);
        System.out.println("Enter choice: ");
        int choice=scan.nextInt();
        if(choice==1)
        {
            System.out.println("Enter diagonal 1 and diagonal 2:");
            int d1=scan.nextInt();
            int d2=scan.nextInt();
            System.out.println("Area of Rhombus: "+(0.5*d1*d2));
        }

        else if(choice==2)
        {
            System.out.println("Enter base and height:");
            int b=scan.nextInt();
            int h=scan.nextInt();
            System.out.println("Area of Rhombus: "+(b*h));
        }

        else
        {
            System.out.println("Enter appropriate choice");
        }

    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93427256/224325711-28daa3bf-2503-4276-8d70-c4640c845a43.png)

## 5.Write a Java program to find the number of days in a month.
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        System.out.println("Enter the month number: ");
        int month=input.nextInt();
        switch(month)
        {
            case 1:
                System.out.println("31 days");
                break;
            case 2:
                System.out.println("28 days");
                break;
            case 3:
                System.out.println("31 days");
                break;
            case 4:
                System.out.println("30 days");
                break;
            case 5:
                System.out.println("31 days");
                break;
            case 6:
                System.out.println("30 days");
                break;
            case 7:
                System.out.println("31 days");
                break;
            case 8:
                System.out.println("31 days");
                break;
            case 9:
                System.out.println("30 days");
                break;
            case 10:
                System.out.println("31 days");
                break;
            case 11:
                System.out.println("30 days");
                break;
            case 12:
                System.out.println("31 days");
                break;
            default:
                System.out.println("Enter appropriate month");
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93427256/224327138-565f6826-4d20-47b3-aeb1-7dd3633eb228.png)


## 6.Write a Java program to print the even numbers from 1 to 20.
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner scan=new Scanner(System.in);
        System.out.print("Enter starting number: ");
        int start=scan.nextInt();
        System.out.print("Enter ending number: ");
        int end=scan.nextInt();

        for(int i=start;i<=end;i++)
        {
            if(i%2==0)
                System.out.print(i+" ");
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93427256/224327622-ec5a5891-afa3-4938-8a20-59d29406a30d.png)


## 7.Write a Java program to create a simple calculator.
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner scan=new Scanner(System.in);
        System.out.print("Enter first operand:");
        int num1=scan.nextInt();
        System.out.print("Enter the operator:");
        String opt=scan.next();
        System.out.print("Enter second operand:");
        int num2=scan.nextInt();
        switch(opt)
        {
            case "+":
                System.out.println(num1+"+"+num2+"="+(num1+num2));
                break;
            case "-":
                System.out.println(num1+"-"+num2+"="+(num1-num2));
                break;
            case "*":
                System.out.println(num1+"*"+num2+"="+(num1*num2));
                break;
            case "/":
                System.out.println(num1+"/"+num2+"="+(num1/num2));
                break;
            case "%":
                System.out.println(num1+"%"+num2+"="+(num1%num2));
                break;
            default:
                System.out.println("Enter appropriate operator");
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93427256/224328312-05ec0cc7-ae56-412a-9206-fc15f47d040e.png)


## 8.Write a Java program to print multiplication table of given number.
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        System.out.print("Enter number: ");
        int num=input.nextInt();
        for(int i=1;i<=10;i++)
            System.out.println(num+"*"+i+"="+(num*i));
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93427256/224328599-a88df945-ce2e-4662-b670-335d763726f3.png)


