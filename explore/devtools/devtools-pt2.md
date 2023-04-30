# DevTools - Debugging

1. The bug was that `result` ended up being a string data type because `num1` and `num2` are both string data types and when adding two string data types without any extra type conversions, the resulting value ends up as a string. This unfortunately does not lead to the solution we are looking for and comes up with putting the two values next to each other rather than adding them as variable.
2. The way I would fix this bug is by converting `num1` and `num2` into number data types so the javascript program ends up adding two numbers rather than string data types.  