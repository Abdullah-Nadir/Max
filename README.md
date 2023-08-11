
# Max

# Learning Goals

- Pass an array into a function
- Create a helper function that finds a maximum value
## Background

There are many situations where you’ll find it helpful to have a function that finds the maximum (and minimum) value in an array. Since there is no built-in max function in C, I have created one in this program. You can use it in your projects where it may be helpful!


## Implementation Details

The main function initializes the array, asks the user to enter values, and then passes the array and the number of items to the max function. The max function iterates through every element in the array, and return the maximum value.


## Usage/Examples

```javascript
max/ $ ./max
Number of elements: 3
Element 0: 2
Element 1: 10
Element 2: -1
The max value is 10.
```

```javascript
max/ $ ./max
Number of elements: 4
Element 0: -100
Element 1: -200
Element 2: -3
Element 3: -5000
The max value is -3.
```
