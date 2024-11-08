# Experiment 3
# Aim:
To demonstrate the usage of arithmetic, assignment, and comparison operators in C++.

# Theory:
Operators in programming languages are symbols that specify which operations to perform on operands. In C++, operators are used extensively to perform various operations on variables and values.

# Code:
```
#include <iostream>

int main() {
    // Arithmetic Operators
    int a = 10;
    int b = 5;
    
    std::cout << "Arithmetic Operators:" << std::endl;
    std::cout << "a + b = " << a + b << std::endl;
    std::cout << "a - b = " << a - b << std::endl;
    std::cout << "a * b = " << a * b << std::endl;
    std::cout << "a / b = " << a / b << std::endl;
    std::cout << "a % b = " << a % b << std::endl;

    // Assignment Operators
    int c = a;
    c += b;
    std::cout << "\nAssignment Operators:" << std::endl;
    std::cout << "c after c += b: " << c << std::endl;
    c -= b;
    std::cout << "c after c -= b: " << c << std::endl;
    c *= b;
    std::cout << "c after c *= b: " << c << std::endl;
    c /= b;
    std::cout << "c after c /= b: " << c << std::endl;
    c %= b;
    std::cout << "c after c %= b: " << c << std::endl;

    // Comparison Operators
    std::cout << "\nComparison Operators:" << std::endl;
    std::cout << "a == b: " << (a == b) << std::endl;
    std::cout << "a != b: " << (a != b) << std::endl;
    std::cout << "a > b: " << (a > b) << std::endl;
    std::cout << "a < b: " << (a < b) << std::endl;
    std::cout << "a >= b: " << (a >= b) << std::endl;
    std::cout << "a <= b: " << (a <= b) << std::endl;

    return 0;
}
```

# Output:
![image](https://github.com/user-attachments/assets/85a0fbe2-b7ce-4c11-a961-6b60659b7ab4)


# Conclusion:
The code successfully demonstrates the use of arithmetic, assignment, and comparison operators in C++. Each section of the code outputs the results of the operations performed, validating the correct implementation and understanding of these operators. Arithmetic operators perform basic mathematical calculations, assignment operators modify the value of a variable based on the operation, and comparison operators help in making decisions by comparing values. This provides a clear understanding of how these operators function in C++.
