# Java Off-by-One Error in Array Iteration
This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error causes an `ArrayIndexOutOfBoundsException` because the loop tries to access an element beyond the array's bounds.
The `Bug.java` file shows the erroneous code.  The `BugSolution.java` file provides the corrected code.
The error is subtle but highlights the importance of carefully checking loop conditions when working with arrays and other indexed data structures.