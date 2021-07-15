# Game-A-Thon: Introduction to Git And Github
# Name : Yashaswi Rewatkar

Problem Statement 1 : Sum of Two numbers

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
    
