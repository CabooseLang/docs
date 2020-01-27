# Caboose Data Types

## Booleans
Booleans consist of `true` or `false`, it's as simple as that! It does get a little complicated when [falsiness](#falsiness) comes into play, so go read there about how it all works.

### Example:
```cb
var a = true;
var b = false;

if (a) {
    // This code will always run
} else {
    // This code never runs
}

var c = !a; // False
```

## Nil
Nil is the caboose equivalent of `null`. Nil is basically a reference to nothing.

### Example:
```cb
var a = nil;

print(a); // Prints out "nil"
```

## Numbers
Numbers are a common data type among almost all programming languages. A number in Caboose can either be an integer or a decimal. They are stored in the same data type.

### Example:
```cb
var a = 0.1;
var b = 1;

print(a + b); // Prints out "1.1"
```

## Strings
Strings are an essential component of all programs. They allow you to store text as a variable.

### Example:
```cb
var a = "Hello, ";
var b = "world";

// Strings can be joined
var c = a + b;

// When printed, they print out the text that they store.
print(c); // Prints out "Hello, world"
```
