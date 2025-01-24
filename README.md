# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that causes this exception, while `bugSolution.java` provides the corrected version.  The error arises from an off-by-one error in a for loop, where the loop index goes beyond the bounds of the array.

## How to Reproduce

1. Compile `bug.java`.
2. Run the compiled code.  You will see an `ArrayIndexOutOfBoundsException`.

## Solution

The solution is provided in `bugSolution.java`.  The corrected loop ensures the index always remains within the valid range of the array.

This example highlights the importance of careful loop index management to avoid common runtime exceptions.