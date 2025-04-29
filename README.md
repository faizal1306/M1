
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read the student percentage and print the grade he/she got?

marks>=70 print A+ GRADE

60>= marks <70 print A GRADE

50>= marks <60 print B GRADE

40>= marks <50 print C GRADE

marks<40 print F GRADE

## ALGORITHM:
1.Start

2.Declare a variable to store the student's percentage.

3.Prompt the user to input the percentage.

4.Read the input value.

5.Use if...else if...else statements to determine the grade:


## PROGRAM:
```
#include <stdio.h>
int main()  
{
    int a;
    scanf("%d",&a);
    if (a>=70)
    printf("A+ GRADE");
    else if ((a>=60)&&(a<70))
    printf("A GRADE");
    else if ((a>=50)&&(a<60))
    printf("B GRADE");
    else if ((a>=40)&&(a<50))
    printf("C GRADE");
    else
    printf("F GRADE");
    return 0;
}
```

## OUTPUT:
![Screenshot 2025-04-29 152911](https://github.com/user-attachments/assets/5aac7e6e-ba81-4632-9afb-7f9a59363dec)

















## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C Program to check the eligibility for college admission if their condition and norms get satisfied using nested if statement. Should satisfy

1. if age above 18 and marks above 60 then it displays "He/She is eligible for college admission"

2. if age above 18 and marks below 60 then it displays "Obtained marks less than 60"

3. if age is below 18 then it displays "Age less than 18"

# ALGORITHM:
1.Start

2.Declare two variables: age and marks.

3.Prompt the user to input age and marks.

4.Read the inputs.

5.Check if age is greater than 18:

6.If true, check if marks > 60:

7.If true, print "He/She is eligible for college admission"

8.Else, print "Obtained marks less than 60"

9.If age is less than or equal to 18:

10.Print "Age less than 18"

11.End

# PROGRAM:
```
#include<stdio.h>
int main(){
    int a,b;
    scanf("%d %d",&a,&b);
    if ((a>=18)&&(b>60))
       printf("He/She is eligible for college admission");
    else if ((a>18)&&(b<60))
       printf("Obtained marks less than 60");
    else
       printf("Age less than 18");
}
```

# OUTPUT:
![Screenshot 2025-04-29 153242](https://github.com/user-attachments/assets/35e0ecc0-cd2c-4cc7-be48-af9ecfcaf726)












# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a C program to swap two numbers without using third variable.

## ALGORITHM:
1.Start

2.Read two numbers, a and b.

3.Set a = a + b

4.Set b = a - b, then a = a - b

5.Print the swapped values of a and b



## PROGRAM:
```
#include <stdio.h>
int main(){
    int a,b;
    scanf("%d%d",&a,&b);
    printf("Numbers before swapping: %d %d\n",a,b);
    printf("Numbers after swapping: %d %d",b,a);
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/732e1d3c-489d-4561-8f5e-02521df97a84)









## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C Program to simulate the bitwise operators(&, | ) using the switch statement

## ALGORITHM:
1.Start

2.Read two integer numbers and a choice (1 for &, 2 for |)

3.Use a switch statement to check the choice

4.If choice is 1, compute a & b; if 2, compute a | b

5.Display the result



## PROGRAM:
```
#include <stdio.h>

int main() {
    int value;

    printf("Enter an integer: ");
    scanf("%d", &value);

    if (value == 1) {
        printf("The value is equal to 1.\n");
    }

    return 0;
}

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/5d4a137d-ff11-4aa4-a0df-0e7c5b316df3)










	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
write a  program to convert temperature from degree celsius to Fahrenheit
## ALGORITHM:
1.Start

2.Read the temperature in Celsius (C).

3.Apply the formula: Fahrenheit = (Celsius * 9/5) + 32

4.Print the result in Fahrenheit.

5.End


## PROGRAM:
```
#include <stdio.h>
int main(){
    float a,b;
    scanf("%f",&a);
    b=(1.8*a)+32;
    printf("%.2f Celsius=%.2f Fahrenheit",a,b);
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/4c7783e4-84a0-4bc7-9861-221581ee2ae5)



## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

