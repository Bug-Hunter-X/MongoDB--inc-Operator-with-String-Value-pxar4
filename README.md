# MongoDB $inc Operator with String Value
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The error occurs when providing a string value instead of a numeric value to the `$inc` operator. This leads to the update operation failing to increment the counter correctly.  The solution demonstrates how to properly use the `$inc` operator with a numeric value.

## Bug
The bug is in the `bug.js` file. The `$inc` operator is used with a string value, which causes the update operation to fail to increment the `count` field correctly.  The solution demonstrates how to correct this error. 