## Conditional Statements-Compare Two Numbers
## Aim
Write a C program to read values of x and y and print whether x == y or x != y using an if-else statement.

## Algorithm
Declare variables x and y.

Read two integers x and y from the user.

Check if x is equal to y using the if statement.

If x is equal to y, print "X is equal to Y".

If x is not equal to y, print "X is NOT equal to Y".

## Program
#include <stdio.h>

int main() {
    int x, y;

    // Read two integers x and y from the user
    printf("Enter two integers: ");
    scanf("%d %d", &x, &y);

    // Check if x is equal to y using an if-else statement
    if (x == y) {
        printf("X is equal to Y\n");
    } else {
        printf("X is NOT equal to Y\n");
    }

    return 0;
}


## Output

Sample OutputIf you enter 10 10:X is equal to YIf you enter 10 20:X is NOT equal to Y

## Result
CODE EXECUTED SUCCESSFULLY 
