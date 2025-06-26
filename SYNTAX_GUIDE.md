# Complete Syntax Guide

This guide details the syntax of the custom language as implemented and evolved throughout the [Guide to Interpreters Series](https://www.youtube.com/playlist?list=PL_2VhOvlMk4UHGqYCLWc6GO8FaPl8fQTh). As of the current episodes, the language is focused on basic arithmetic, variable declarations, and expressions. This document will be updated as new features are added.

---

## 1. Lexical Structure

### 1.1. Whitespace
- **Ignored** except to delimit tokens.
- Includes spaces (` `), tabs (`\t`), and newlines (`\n`).

### 1.2. Comments
- **Not yet implemented.**  
  (Future episodes may add support for comments.)

---

## 2. Tokens

### 2.1. Keywords

| Keyword | Description                |
|---------|----------------------------|
| `let`   | Declares a variable        |

### 2.2. Identifiers

- Must start with an alphabet character (`a-z` or `A-Z`)
- May contain only alphabet characters (no numbers or underscores as of current episodes)
- Examples:
  - `x`
  - `variable`
  - `result`

### 2.3. Literals

#### Numeric Literals

- Only integers are supported.
- Examples:
  - `5`
  - `123`
  - `0`

---

## 3. Operators

| Operator | Name             | Usage Example      |
|----------|------------------|-------------------|
| `+`      | Addition         | `a + b`           |
| `-`      | Subtraction      | `a - b`           |
| `*`      | Multiplication   | `a * b`           |
| `/`      | Division         | `a / b`           |
| `=`      | Assignment       | `let x = 10`      |

- **Only these binary operators are supported currently.**
- Parentheses `(`, `)` are used for grouping.

---

## 4. Statements

### 4.1. Variable Declaration

```plaintext
let <identifier> = <expression>
```
**Examples:**
```plaintext
let x = 5
let sum = a + b
```

### 4.2. Expression Statement

Any valid expression can be written by itself.

**Examples:**
```plaintext
1 + 2
a * (b + 3)
```

---

## 5. Expressions

### 5.1. Numeric Literal

```plaintext
42
```

### 5.2. Identifier

```plaintext
myVar
```

### 5.3. Binary Expression

```plaintext
<expression> <operator> <expression>
```
**Examples:**
```plaintext
a + b
x * (y - 2)
```

### 5.4. Parenthesized Expression

```plaintext
(expression)
```
**Example:**
```plaintext
(a + b) * 3
```

---

## 6. Program Structure

- A program is a sequence of statements.
- Each statement is separated by a newline or whitespace.

**Example Program:**
```plaintext
let a = 10
let b = 20
let sum = a + b
(sum + 5) * 2
```

---

## 7. Error Handling

- **Unrecognized characters** will cause an error and terminate interpretation.
- **Only supported tokens and keywords are allowed.**
- **No error recovery** is implemented as of current episodes.

---

## 8. Future Features

The following features are not yet implemented but may appear in future episodes:
- Floating point literals
- String literals
- Boolean logic and comparison operators
- Control flow (if, while, etc)
- Functions and scopes
- Comments

---

## 9. Example Code

```plaintext
let num = 7
let double = num * 2
let result = (double + 3) / 5
result
```

---

## 10. Reference

- [Interpreter Series Playlist](https://www.youtube.com/playlist?list=PL_2VhOvlMk4UHGqYCLWc6GO8FaPl8fQTh)
- [JSimplified Channel](https://www.youtube.com/c/JSimplified)
- [Community Discord](https://discord.gg/KEfHqZ3zn7)

---

*This syntax guide will be updated as new language features are added in future episodes.*
