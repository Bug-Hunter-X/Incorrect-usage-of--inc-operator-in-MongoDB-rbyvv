# Incorrect usage of $inc operator in MongoDB
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB.  The `$inc` operator is used to increment a numerical field by a specified value. However, in this example, we attempt to increment the `counter` field by a string value which leads to an error.
The solution provides the corrected way to use the `$inc` operator, ensuring that the increment value is a number.
