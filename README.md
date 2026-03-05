# Programming Exercises

A collection of programming exercises demonstrating functional programming concepts in Dart and Kotlin.

## Overview

This project contains exercises that practice key functional programming concepts including:
- Filtering collections
- Mapping/transforming data
- Using predicate functions
- Working with collections (List, Map)
- Calculating aggregates (average)

## Project Structure

```
Exercises/
├── Exercise_dart_version/
│   ├── exercise1/     - Filter and square numbers
│   ├── exercise2/      - Filter with predicate function
│   ├── exercise3/     - Map words to lengths
│   └── exercise4/     - Filter and calculate average
│
└── kotlin_version/
    ├── Execises 1/     - Filter with predicate (Kotlin)
    ├── Exercise 2/     - Map words to lengths (Kotlin)
    └── Exercise 3/     - Filter and calculate average (Kotlin)
```

## Exercises

### Dart Exercises

| Exercise | Description |
|----------|-------------|
| [exercise1](Exercise_dart_version/exercise1/main.dart) | Filters numbers greater than 5, squares them, and prints the result |
| [exercise2](Exercise_dart_version/exercise2/main.dart) | Demonstrates higher-order functions with predicate filtering |
| [exercise3](Exercise_dart_version/exercise3/main.dart) | Creates a map of word lengths and filters by length > 4 |
| [exercise4](Exercise_dart_version/exercise4/main.dart) | Filters people by name starting with 'A' or 'B', calculates average age |

### Kotlin Exercises

| Exercise | Description |
|----------|-------------|
| [Exercise 1](kotlin_version/Execises%201/src/Main.kt) | Kotlin version of predicate filtering (even numbers) |
| [Exercise 2](kotlin_version/Exercise%202/src/Main.kt) | Kotlin version of word length mapping and filtering |
| [Exercise 3](kotlin_version/Exercise%203/src/Main.kt) | Kotlin version of person filtering and average calculation |

## Running the Exercises

### Dart

```bash
dart run Exercise_dart_version/exercise1/main.dart
dart run Exercise_dart_version/exercise2/main.dart
dart run Exercise_dart_version/exercise3/main.dart
dart run Exercise_dart_version/exercise4/main.dart
```

### Kotlin

```bash
kotlinc Exercise_3/src/Main.kt -include-runtime -d Main.jar
java -jar Main.jar
```

Or use an IDE like IntelliJ IDEA with Kotlin plugin.

## Concepts Covered

- **Lambda Functions**: Anonymous functions used for filtering and mapping
- **Higher-Order Functions**: Functions that take other functions as parameters
- **Predicate Functions**: Functions that return boolean values
- **Collection Operations**: `filter()`, `map()`, `where()`, `associateWith()`
- **Data Classes**: Kotlin's data class for modeling objects
- **Type Declarations**: Dart's strong typing with `List<int>`, `String`, etc.
