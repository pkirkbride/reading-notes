# Read: 08 - Operators and Loops

## Operators

### Assignment operators

Assignment operators assign the value to the right of the operator to the variable on the left of the operator. It looks like an equal sign, which is somewhat intuitive on the surface.

Chaining assignments or nesting assignments can result in surprising behavior, so some JavaScript style guides discourage it.  There are some occasions when they could legitimately be used, so it’s important to understand how they work.

### Comparison operators

Comparison operators compare the values on both sides and return a true or false value. They are variations on equal, greater than, and less than.

If they’re not the same type (e.g. number and string), JavaScript will try to convert them to a type that can be compared. The only two exceptions to this are `===` (strict equal) and `!==` (strict not equal), which will not try to convert the number types.

## Loops

### `For` statements

`For` loops continue to repeat until the defined condition becomes false. At that point, the statement will be executed.

### `While` statements

`While` loops continue to execute as long as the defined condition is true. Once it becomes false, the loop will stop.

One issue to keep in mind is that the condition must eventually become false for a loop to stop. If it’s not guaranteed that the condition will become false, you’ve created an infinite loop.

### For vs while

While these two types of loops seem similar, there are situations when one would be better than the other. At a high level, `for` loops are good when you know how many times a loop should be run. `While` can be used in situations when you don’t necessarily know how many tries a loop will need to repeat to accomplish the task.
