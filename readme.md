This repository contains some information about the differences between JavaScript and Python.

## JavaScript vs Python

### 1. Syntax

JavaScript uses curly braces `{}` to define blocks of code. Semicolons `;` are used to separate statements.

Python uses indentation to define blocks of code. Semicolons `;` are not required to separate statements.

Whitespace is important in Python, but not in JavaScript.

#### JavaScript

```javascript
console.log("Hello, World!");
```

#### Python

```python
print("Hello, World!")
```

### 2. Variables

JavaScript has two ways to declare variables: `let` and `const`. `let` is used to declare variables that can be reassigned, while `const` is used to declare variables that cannot be reassigned. In Python, variables are declared using the `=` operator, no special keyword is required.

#### JavaScript

```javascript
let x = 5;
const y = 10;
```

#### Python

```python
x = 5
```

### 3. Functions

In JavaScript, functions are defined using the `function` keyword, or the arrow `=>` syntax for arrow functions. In Python, functions are defined using the `def` keyword.

#### JavaScript

```javascript
// Function keyword
function add(a, b) {
  return a + b;
}

// Arrow function
const add = (a, b) => a + b;
```

#### Python

```python
def add(a, b):
    return a + b
```

### 4. Loops

JavaScript has `for`, `while`, and `do...while` loops. Python has `for` and `while` loops.

#### JavaScript

```javascript
for (let i = 0; i < 5; i++) {
  console.log(i);
}

let i = 0;
while (i < 5) {
  console.log(i);
  i++;
}
```

#### Python

```python
for i in range(5):
    print(i)

i = 0
while i < 5:
    print(i)
    i += 1
```

### 5. Classes

JavaScript uses the `class` keyword to define classes. Python also uses the `class` keyword.

#### JavaScript

```javascript
class Person {
  constructor(name) {
    this.name = name;
  }

  greet() {
    console.log(`Hello, my name is ${this.name}`);
  }
}

const person = new Person("Alice");
person.greet();
```

#### Python

```python
class Person:
    def __init__(self, name):
        self.name = name

    def greet(self):
        print(f"Hello, my name is {self.name}")

person = Person("Alice")
person.greet()
```

### 6. Libraries

JavaScript has a rich ecosystem of libraries and frameworks, such as React, Angular, and Vue. Python also has a wide range of libraries, such as NumPy, Pandas, and Django.
