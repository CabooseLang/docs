# Conditionals & Loops

## If/Else Statements
If-else statements are essential to programming. Caboose's if-else statements reuire brackets.

### Example:
```cb
if (true) {
    print("This code always runs");
} else {
    print("This code never runs");
}
```

## For Loops
For loops are the best known kind of loop, and one of the most complicated loop structures there are. For loops accept three parameters in the form of `1; 2; 3`:
- The initializer (e.g. `var i = 0`)
- The condition (e.g. `i < 5`)
- The counter (e.g. `i = i + 1`)
If you don't pass values to the for loop, and instead pass two semicolons (`;;`), the loop will go forever.

> **Note:** A for loop with one statement in its body can omit its braces.

### Example:
```cb
// Create a regular for loop
for(var i = 0; i < 10; i = i + 1) print(i);

// Create an infinite for loop
for(;;) print("This loops forever!")
```

## While Loops
While loops are much simpler than for loops, although less known. They take one parameter, which is a condition.

> **Note:** A while loop with one statement in its body can omit its braces.

### Example:
```cb
// Create an infinite while loop
while(true) print("This loops forever!");

// Create a regular while loop
var i = 0;
while(i < 10) {
    print(i);
    i = i + 1;
}
```
