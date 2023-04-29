# Part 1. A Quick Introduction

## var declaration 
1. `values added:  20`
2. `values added:  20`<br>`final result:  20`


## let declaration
3. `values added:  20`
4. `values added:  20`<br>By line 13, a `ReferenceError` is returned because `result` isn't defined because `let` makes the variable `result` only accessable within the block it is defined in.

## const declaration
1. By line 9, a `TypeError` because `const` makes it so `result` can not be redefined and line 7 tries to assign a value to the constant variable. 
2. By line 13, a `TypeError` because `const` makes it so `result` can not be redefined and line 7 tries to assign a value to the constant variable.