# PHP Loose Comparison Pitfalls with null and undefined

This example demonstrates a common error in PHP related to loose comparison when handling null and undefined values.  Loose comparison (==) can lead to unexpected results, especially when dealing with values that might evaluate to false in a boolean context (like 0, "", or false itself).  Strict comparison (===) is recommended to avoid these issues.

The `bug.php` file contains code exhibiting the issue, while `bugSolution.php` provides a corrected version using strict comparison.

## How to Reproduce
1.  Clone this repository.
2. Run `bug.php` using a PHP interpreter. Observe the unexpected outputs.
3. Run `bugSolution.php` for the corrected output.