### Swift Basics Cheat Sheet


#### 1. Variables & Constants
- **Graphic**: A labeled container for variables and an unchangeable box for constants.
- **Snippet**: `var age = 30` and `let name = "Taylor"`
- **Tip**: Use `var` for changing values and `let` for values that won't change.

#### 2. Functions
- **Graphic**: A factory processing inputs to outputs.
- **Snippet**: `func greet(name: String) -> String { return "Hello, \(name)!" }`
- **Tip**: Functions are the building blocks of reusable code.

#### 3. Operators
- **Visual**: Arithmetic operators (+, -, *, /) shown with numbers, and Boolean operators (&&, ||, !) with light switches on/off.
- **Example**: `1 + 2` and `true && false`
- **Mnemonic**: "Adding to your knowledge, dividing problems, and switching conditions."

#### 4. Classes & Instances
- **Graphic**: A blueprint (class) next to a house (instance).
- **Snippet**: `class Dog { var name: String }` and `let myDog = Dog()`
- **Fact**: Classes are reference types - share and modify the same instance.

#### 5. Control Flow
- **Comic Strip**: Characters deciding (if-else) paths at a crossroad, looping (for, while) in a maze, and switch-case as a control panel.
- **Snippet**: `if score > 50 { pass() } else { fail() }`

#### 6. Loops
- **Graphic**: A racetrack for `for-in`, a treadmill for `while`, and a stair stepper for `repeat-while`.
- **Code**: `for i in 1...5 { print(i) }`

#### 7. Conditionals
- **Visual**: Traffic lights for if-else statements.
- **Example**: `if light == .green { go() } else { stop() }`

#### 8. Strings
- **Illustration**: A string with characters as beads.
- **Snippet**: `let word = "Hello, Swift!"`
- **Tip**: Strings are collections of characters.

#### 9. Dictionaries
- **Graphic**: A dictionary book with key-value pairs.
- **Code**: `var capitals = ["France": "Paris", "Japan": "Tokyo"]`

#### 10. Arrays
- **Visual**: A shelf with ordered boxes.
- **Example**: `var fruits = ["Apple", "Banana", "Cherry"]`
- **Note**: Arrays keep order; dictionaries do not.

#### 11. Closures
- **Illustration**: A magic box with inputs leading to an output.
- **Snippet**: `{ (parameters) -> return type in statements }`
- **Mnemonic**: "Closures capture and store references to constants and variables from the context in which they are defined."

#### 12. Guard Statements
- **Comic**: A knight (guard) protecting a castle from bad input.
- **Code**: `guard condition else { return }`
- **Tip**: Use `guard` for early exits in functions.

#### 13. Tuples
- **Graphic**: A backpack with different types of items.
- **Example**: `var person = (name: "John", age: 30)`
- **Fact**: Tuples group multiple values into a single compound value.

#### 14. Enumerations
- **Visual**: A collection of badges for different weather types.
- **Code**: `enum Weather { case sun, rain, wind }`
- **Tip**: Enums define a common type for a group of related values.

#### 15. Swift Reminders
- **Checklist**: Swift safety tips, such as unwrapping optionals carefully, preferring `let` over `var`, and using type inference.
- **Motivation**: "Keep coding and Swift will become your second language!"

#### 16. Footer
- A footer encouraging practice and exploration.
- **Quote**: "The Swift way: Learn by doing, improve by iterating."
