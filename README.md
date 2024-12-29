# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value. However, if you try to increment with a string value instead of a numerical value, you'll encounter an error.

## Bug

The bug arises from providing a string value to the `$inc` operator.  MongoDB expects a numerical value for the increment. 

## Solution

The solution involves providing a numerical value (integer or float) to the `$inc` operator. Make sure the field to be incremented is also a numerical type.
