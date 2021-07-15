# Game-A-Thon: Introduction to Git And Github
# Name : Yashaswi Rewatkar

# Problem Statement 1 : Sum of Two numbers

TestCase 1 : input : 12,6  Output : 18

#include <stdio.h>
int main() {    

    int number1, number2, sum;
    
    printf("Enter two integers: ");
    scanf("%d %d", &number1, &number2);

    // calculating sum
    sum = number1 + number2;      
    
    printf("%d + %d = %d", number1, number2, sum);
    return 0;
}
    
# Problem Statement 2 : Write the program for Increment and Decrement Operators

TestCase 2 : Output : ++a = 11
--b = 99
++c = 11.500000
--d = 99.500000

// Working of increment and decrement operators

#include <stdio.h>

int main()

{
    int a = 10, b = 100;
    
    float c = 10.5, d = 100.5;

    printf("++a = %d \n", ++a);
    printf("--b = %d \n", --b);
    printf("++c = %f \n", ++c);
    printf("--d = %f \n", --d);

    return 0;
}

