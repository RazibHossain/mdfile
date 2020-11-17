# .md file Demo
Created By Razib Hossain
Date: 17-11-2020
---
### Write a program which calculate Factorial of a number.

**Input**
1. For 0,1 it returns 1.
2. Number will be non-negative.

**Hints**
The following logic should be maintain.

![Factorial](https://cdn.educba.com/academy/wp-content/uploads/2019/09/Factorial-in-C.png)

**Description**
| Option | Description |
| ------ | ----------- |
| Languages | C++, Java, python  |
| Time |   1s |
|IDE|Codeblocks,Eclipse|

### Solution
**`c++`**



    #include <stdio.h>
    int main() {
    int n, i;
    unsigned long long fact = 1;
    printf("Enter an integer: ");
    scanf("%d", &n);

    // shows error if the user enters a negative integer
    if (n < 0)
        printf("Error! Factorial of a negative number doesn't exist.");
    else {
        for (i = 1; i <= n; ++i) {
            fact *= i;
        }
        printf("Factorial of %d = %llu", n, fact);
    }

    return 0;
    }

**Output**
```
Enter an integer: 10
Factorial of 10 = 3628800
```
[Problem Online](https://www.programiz.com/c-programming/examples/factorial)
 
  
  