# cpp-swap-call-by-value
C++ 
# C++ Swap Using Call by Value

This repository contains a simple C++ program that demonstrates **swapping two variables using call by value**.

## 📌 Program Explanation
- The swap function receives **copies** of the original variables.
- Changes made inside the function **do not affect** the original variables.
- This clearly explains the behavior of call by value in C++.

## 🧠 Concepts Covered
- Call by value
- Function parameter passing
- Variable scope
- Swapping logic

## 💻 Source Code
```cpp
#include<iostream>
using namespace std;

void swap(int x, int y) {
    int temp;
    temp = x;
    x = y;
    y = temp;
    cout << x << " " << y << endl;
}

int main() {
    int a = 10, b = 48;
    swap(a, b);
    cout << a << " " << b << endl;
    return 0;
}
