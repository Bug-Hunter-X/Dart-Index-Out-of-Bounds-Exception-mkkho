# Dart Index Out of Bounds Example

This repository demonstrates a common error in Dart programming: the `IndexOutOfRangeException`. This exception is thrown when you try to access an element in a list (or other indexable data structure) using an index that is outside the valid range of indices.

The `bug.dart` file contains code that produces the error. The `bugSolution.dart` file demonstrates how to prevent this error using proper bounds checking.

## How to Reproduce

1. Clone this repository.
2. Open the `bug.dart` file in a Dart editor.
3. Run the code. You should see an exception similar to:
```
Uncaught Error: RangeError (index): Invalid value: Not in inclusive range 0..4: 5
```

## Solution

The `bugSolution.dart` file shows how to avoid this error by checking the index before accessing it. You can also use the `length` property to determine the upper bound index.