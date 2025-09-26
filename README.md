# StudentRegistration
### JavaScript Bootcamp Registration System

A console-based student management system for bootcamp enrollment, demonstrating object-oriented programming, input validation, and duplicate prevention in JavaScript.

## Overview

This Node.js application simulates a bootcamp registration system where students can enroll in coding programs. The system includes user validation, duplicate prevention, and comprehensive testing to ensure data integrity.

## Features

- **Student Registration**: Create and manage student profiles with name and email
- **Bootcamp Management**: Handle multiple bootcamp programs with different levels
- **Duplicate Prevention**: Prevent duplicate email registrations automatically
- **Input Validation**: Validate student information before registration
- **Comprehensive Testing**: Built-in test suite covering all functionality

## Classes

### Student Class
```javascript
class Student {
    constructor(name, email)
    // Creates student objects with name and email validation
}
```

### Bootcamp Class
```javascript
class Bootcamp {
    constructor(name, level, students = [])
    registerStudent(studentToRegister)  // Registers students with validation
    listStudents()                      // Lists all registered students
}
```

## Key Methods

- **registerStudent()**: Validates and registers students with duplicate email prevention
- **listStudents()**: Displays all registered students or indicates if none are registered
- **Input Validation**: Checks for valid name and email before registration
- **Error Handling**: Provides appropriate console messages for various scenarios

## How to Run

```bash
node registration.js
```

## Sample Output

```
TASK 1: PASS - Student class functionality
TASK 2: PASS - Bootcamp class initialization
TASK 3: PASS - Student registration with validation
TASK 4: PASS - Student listing functionality

All tests completed successfully!
```

## Technical Implementation

- **Language**: JavaScript (ES6+)
- **Runtime**: Node.js
- **Dependencies**: None (vanilla JavaScript)
- **Architecture**: Object-oriented with class-based design
- **Testing**: Built-in validation tests for all features

## Use Cases

- **Educational Projects**: Learn JavaScript OOP concepts
- **Bootcamp Systems**: Student enrollment management
- **Registration Platforms**: General registration system template
- **Testing Practice**: Example of comprehensive testing methodology

## Educational Value

This project demonstrates:
- Class-based object-oriented programming in JavaScript
- Input validation and error handling
- Duplicate data prevention
- Array manipulation and student management
- Testing methodology and validation

## Requirements

- Node.js (any modern version supporting ES6 classes)
- No external dependencies required

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
