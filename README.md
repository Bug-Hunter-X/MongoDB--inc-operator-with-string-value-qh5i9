# MongoDB $inc operator with string value
This code snippet demonstrates an incorrect usage of the $inc operator in MongoDB. The $inc operator requires a numeric value. Using a string will result in an error.  The solution shows the correct implementation.

## Bug
The original code attempts to increment the `count` field with a string value ('1'). This leads to a failure.

## Solution
The solution uses the correct numeric value for incrementing the field.