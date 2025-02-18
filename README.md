# MongoDB $inc Operator Error: Using String Instead of Number

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The error occurs when attempting to increment a field using a string value instead of a numerical value. This can lead to unexpected results or errors. The solution shows how to correct this issue.

## Bug
The original code incorrectly uses a string value ('1') with the `$inc` operator, which is intended for numerical increment operations. 

## Solution
The corrected code uses a numerical value (1) with the `$inc` operator, ensuring the correct increment behavior.
