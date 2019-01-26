# Number

A *Number* is either a whole number or a number with a fractional part.

### @parent blocks/language

An integer *Number* such as `42` or `-42` is a signed 32-bit integer (two's complement).
A floating point number such as `3.1416` is a 64 bit double precision floating point number.

### Declare a number variable

You can assign a number to a variable:

#### #declareexample

```block
let num = 42;
let pi = 3.1416;
```

### Arithmetic operators

The following arithmetic operators work on numbers and return a [Number](/types/number):

* addition: `1 + 3`
* subtraction: `1 - 3 `
* multiplication: `3 * 2`
* integer division: `7 / 3`
* modulo is available through the [math library](/blocks/math)

### Relational operators

The following relational operators work on numbers and return a [Boolean](/blocks/logic/boolean):

* equality: `(3 + 1) = 4`
* inequality: `3 != 4`
* less or equal than: `3 <= 4`
* less than: `3 < 4`
* greater or equal than : `4 >= 3`
* greater than: `4 > 3`

## #print

### Functions that return a number

Some functions return a number, which you can store in a variable. 

### #functionreturnexample

```block
let abs = Math.abs(-42);
```

### Math functions

The [math library](/blocks/math) includes math related functions. For example, the `min` function returns the minimum value of two input parameters `x` and `y`:

```block
let lowest = Math.min(-42, 1000);
```

### See also

[math](/blocks/math), [var](/blocks/variables/var), [Boolean](/blocks/logic/boolean)
