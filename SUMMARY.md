# Learn a New Programming Language

## 1. Introduction & Philosophy
Modern programming languages often share similar concepts. Instead of learning from scratch, use your existing knowledge to map concepts to the new language. This guide focuses on efficiently learning syntax, data structures, and standard libraries by leveraging what you already know.

## 2. Preparation (The Trivia)
Before coding, spend 5-10 minutes understanding the language's meta-data:
*   **Type**: General purpose? Compiled or Interpreted? Static or Dynamic? Garbage collected?
*   **Paradigm**: OOP, Functional, or Multi-paradigm?
*   **History & Purpose**: What problem does it solve? What influenced it?
*   **Ecosystem**: Popular frameworks, library support, and typical use cases (Web, Systems, AI).

## 3. Core Syntax (The Fast Track)
Focus on syntax and basic constructs. Don't worry about best practices yet.

### Basic Setup
*   **Hello World**: Standard output syntax.
*   **Entry Point**: layout of `main` function or script execution.
*   **Comments**: Single and multi-line syntax.

### Variables & Types
*   **Declaration**: Syntax for defining variables (e.g., `var`, `let`, `type name`).
*   **Initialization**: Default values for uninitialized variables?
*   **Constants**: Syntax for immutable variables.
*   **Primitive Types**: access modifiers, Integers, Floats, Booleans, Strings, Arrays.
*   **Casting**: Explicit vs. Implicit casting. `type(val)` vs `(type)val`.

### Operators
*   **Arithmetic**: `+`, `-`, `*`, `/`, `%`, `**` (power).
*   **Comparison**: `==`, `!=`, `<`, `>`, reference vs value equality.
*   **Logical**: `&&` (AND), `||` (OR), `!` (NOT).
*   **Bitwise**: `&`, `|`, `^`, `<<`, `>>`.
*   **Ternary**: `condition ? true : false`.

### Control Flow
*   **Conditionals**: `if`, `else if`, `else`, `switch/match`.
*   **Loops**: `while`, `for` (standard & iterator/foreach), `break`, `continue`.
*   **Scope**: Block scope vs Function scope.

### Functions
*   **Signature**: Return types, parameter types.
*   **Parameters**: Pass-by-value vs Pass-by-reference. Default arguments.
*   **Advanced**: Overloading, Variadic functions, Lambdas/Anonymous functions.

## 4. Data Structures & Algorithms
Learn the standard library implementations of common data structures.

### Memory & Basics
*   **Storage**: Stack vs Heap.
*   **References**: Deep vs Shallow copies.
*   **Null Safety**: Existence of `null`/`nil`.

### Common Operations (CRUD)
For all structures (Arrays, Lists, Maps), learn:
1.  **Access**: Get element at index/key.
2.  **Insert**: Head, tail, specific position.
3.  **Delete**: Remove by value or index.
4.  **Search**: Contains/Exists check.
5.  **Metrics**: Length/Size.
6.  **Slicing**: Sub-arrays/Sub-strings.

### Linear Structures
*   **Strings**: concatenation, interpolation, specific methods (`startsWith`).
*   **Arrays/Vectors**: Dynamic resizing?
*   **Tuples/Pairs**: Immutable groups.
*   **Stacks/Queues/LinkedLists**: Standard implementations.
*   **Maps/Dictionaries**: HashMap (Unordered) vs TreeMap (Ordered).
*   **Sets**: Unique item collections.

### Algorithms
*   **Sorting**: Default sort, custom comparators, reverse sort.
*   **Search**: Binary search, lower/upper bounds.
*   **Math**: `min`, `max`, `round`, `floor`, `ceil`, `pow`, `sqrt`, `random`.

## 5. Object-Oriented Programming (OOP)
If the language supports OOP:

### Basics
*   **Class Definition**: Syntax, Fields (static/instance), Methods.
*   **Instantiation**: Constructors (`new` keyword?), Destructors.
*   **Access Control**: `public`, `private`, `protected`.
*   **`this`/`self`**: Reference to current instance.

### Principles
*   **Encapsulation**: Getters/Setters.
*   **Inheritance**: `extends` keyword, Single vs Multiple inheritance.
*   **Polymorphism**: Overriding methods, Abstract classes, Interfaces/Protocols.
*   **Generics**: Syntax for type parameters `<T>`.

## 6. Functional Programming
*   **Map**: Transform a collection.
*   **Filter**: Select elements based on a predicate.
*   **Reduce**: Accumulate values (fold).
*   **Closures**: Capturing environment variables.

## 7. System & I/O
Interact with the OS and filesystem.

### Files
*   **Read**: Line-by-line vs whole file.
*   **Write**: Append vs Overwrite modes.
*   **Paths**: Joining paths, checking existence (`isFile`, `isDir`).

### Terminal
*   **Args**: Reading command line arguments.
*   **Input**: Reading from `stdin`.
*   **Execution**: Running external shell commands.
