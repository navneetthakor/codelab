# Abstract
Codelab is initiative taken by our prof. Mohsin Hasan sir.

## Conditional statement related questions for C language

1. Quesion:
    ```
    Write a C program that takes an integer input from the user and checks if the number is positive. Print "Positive Number" if the condition is true. (use if statement)

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
    ```

    - 4th
    ```
    Enter an Integer: -7
    ```

2. Quesion:
    ```
    Write a C program that checks if a number is even or odd. If even, print "Even Number", otherwise print "Odd Number". (use if-else statement)

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

3. Quesion:
    ```
    Write a C program that takes a number as input and checks whether it is positive, negative, or zero. Print the appropriate message. (Use if-else ladders)

    - syntax of "if-else ladders"

    if (condition1) {
        // code to be executed if condition1 is true
    } else if (condition2) {
        // code to be executed if condition2 is true
    } else {
        // code to be executed if all conditions are false
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
        } else if (num < 0) {
            printf("Negative Number");
        } else {
            printf("Zero");
        }

        return 0;
    }

    ```

    test cases:
    - 1st (Visible to user)
    ```
    Enter an Integer: 80
    Positive Number
    ```
    - 2nd
    ```
    Enter an Integer: 6
    Positive Number
    ```

    - 3rd
    ```
    Enter an Integer: -101
    Negative Number
    ```

    - 4th
    ```
    Enter an Integer: 0
    Zero
    ```


4. Quesion:
    ```
    Write a C program that takes two integer inputs and checks if both numbers are greater than 10. If true, print "True", otherwise print "False". (used Nested-if statement)

    - syntax of "Nested-if statement"

    if (condition1) {
        if (condition2) {
            // code to be executed if condition1 and condition2 are true
        }
    }


    ```

    Code:
    ```
    #include <stdio.h>

    int main() {
        int num1, num2;
        printf("Enter two integers: ");
        scanf("%d %d", &num1, &num2);

        if (num1 > 10) {
            if (num2 > 10) {
                printf("True");
            } else {
                printf("False");
            }
        } else {
            printf("False");
        }

        return 0;
    }


    ```

    test cases:
    - 1st (Visible to user)
    ```
    Enter two integers: 8 18
    False
    ```
    - 2nd
    ```
    Enter two integers: 80 555
    True
    ```

    - 3rd
    ```
    Enter two integers: 0 0
    False
    ```

    - 4th
    ```
    Enter two integers: 70 7
    False
    ```


