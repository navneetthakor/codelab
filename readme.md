# Abstract
Codelab is initiative taken by our prof. Mohsin Hasan sir.

## Conditional statement related questions for C language

1. Quesion:
    ```
    Write a C program that takes an integer input from the user and checks if the number is positive. Print "Positive Number" if the condition is true.

    - syntax of "if statement"

    if (condition) {
    // code to be executed if the condition is true
    }

    ```

    Code:
    ```
    #include <stdio.h>

    int main() {
        int num;
        printf("Enter an integer: ");
        scanf("%d", &num);

        if (num > 0) {
        printf("Positive Number");
        }

        return 0;
    }

    ```

    test cases:
    - 1st (Visible to user)
    ```
    Enter an Integer: 5
    Positive Number
    ```
    - 2nd
    ```
    Enter an Integer: 15
    Positive Number
    ```

    - 3rd
    ```
    Enter an Integer: 0
    (no output)
    ```

    - 4th
    ```
    Enter an Integer: -7
    (no output)
    ```

2. Quesion:
    ```
    Write a C program that checks if a number is even or odd. If even, print "Even Number", otherwise print "Odd Number".

    - syntax of "if-else statement"

    if (condition) {
        // code to be executed if the condition is true
    } else {
        // code to be executed if the condition is false
    }

    ```

    Code:
    ```
    #include <stdio.h>

    int main() {
        int num;
        printf("Enter an integer: ");
        scanf("%d", &num);

        if (num % 2 == 0) {
            printf("Even Number");
        } else {
            printf("Odd Number");
        }

        return 0;
    }

    ```

    test cases:
    - 1st (Visible to user)
    ```
    Enter an Integer: 8
    Even Number
    ```
    - 2nd
    ```
    Enter an Integer: 36
    Even Number
    ```

    - 3rd
    ```
    Enter an Integer: 101
    Odd Number
    ```

    - 4th
    ```
    Enter an Integer: 0
    Even Number
    ```


