# Array Printing Template Function

A simple C++ program demonstrating a template function that can print arrays of any data type.

## Description

This program implements a generic template function `printArray()` that can display elements of an array regardless of the data type. It showcases the flexibility of function templates in handling array operations.

### Key Features
- Generic array printing functionality
- Template function implementation
- Support for any printable data type
- Array traversal demonstration

## Function Template Structure

```cpp
template <class T>
void printArray(T arr[], int size) {
    for (int i = 0; i < size; i++) {
        cout << arr[i] << " ";
    }
    cout << endl;
}
