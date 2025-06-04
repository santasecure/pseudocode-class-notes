
# Pseudocode Notes for IT 1090C

## Pseudocode Structure
```
class ClassName
   main()
      // Variable Declarations
      // Logic and Code Statements
   return
end class
```
- 'class' and 'end class' must be lowercase.
- 'main()' and 'return' wrap all code logic.
- Indent 3 spaces inside 'main()'.
- Use CamelCase for variable names (e.g., totalPrice, customerName).
- Use ALL_CAPS for symbolic constants (e.g., FREE_SHIPPING_THRESHOLD).

## 📚 Variable Declarations

| Pseudocode Type | Example                   |
|-----------------|---------------------------|
| num             | num price = 0              |
| String          | String customerName = ""   |
| boolean         | boolean isFinished = false |

## 🔁 Loops

### While Loop (Indefinite, Pre-Test)
```
while CONDITION
   // Statements
end while
```

### For Loop (Definite, Pre-Test)
```
for counter = start to end step increment
   // Statements
end for
```

### Do While Loop (Indefinite, Post-Test)
```
do
   // Statements
while CONDITION
```

## 🔀 Conditionals

### Simple If
```
if CONDITION then
   // Statements
end if
```

### If-Else
```
if CONDITION then
   // True statements
else
   // False statements
end if
```

### Else If (Cascaded If)
```
if CONDITION then
   // Block 1
else if CONDITION then
   // Block 2
else
   // Default Block
end if
```

## Boolean Expressions
- Relational Operators:
  - == (equals)
  - != (not equals)
  - <  (less than)
  - >  (greater than)
  - <= (less than or equal to)
  - >= (greater than or equal to)
- Logical Operators:
  - AND
  - OR

## Best Practices
- Always prompt the user for input.
- Output results clearly and in a readable format.
- Use descriptive variable names in CamelCase.
- Constants should be named in ALL_CAPS.
- Indent properly for clarity (3 spaces after 'main()').
