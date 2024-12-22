# MongoDB $inc operator error with string value
This repository demonstrates an uncommon error in MongoDB when using the $inc operator with a string value instead of a numerical value. The $inc operator is designed to increment a numerical field by a specified value. However, providing a string value will lead to an unexpected result or error.

## Bug Description
The bug arises when the `$inc` operator is used in a MongoDB update operation with a string value for the increment. This results in the operation not working as intended and potentially unexpected output.

## Bug Solution
The solution is to ensure that the value provided to the `$inc` operator is a numerical value (integer or floating-point number).