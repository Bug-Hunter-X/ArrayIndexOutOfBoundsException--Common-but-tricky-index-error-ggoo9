# ArrayIndexOutOfBoundsException: A subtle Java bug

This repository demonstrates a common, yet easily overlooked, error in Java: the `ArrayIndexOutOfBoundsException`.  While seemingly simple, this error can be tricky to debug in larger projects. 

The `UncommonBug.java` file contains code that attempts to access an array index beyond the array's valid range, leading to the exception.  The `UncommonBugSolution.java` file provides the corrected code, highlighting the solution.

This example is intended to help improve understanding of array manipulation and the importance of carefully checking loop conditions when working with arrays in Java.