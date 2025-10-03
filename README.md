# StudentRegistration
### JavaScript Bootcamp Registration System

![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-blue)
![Status](https://img.shields.io/badge/status-active-success)

A console-based student management system for bootcamp enrollment, demonstrating object-oriented programming, input validation, and duplicate prevention in JavaScript.

## Screenshots

> **Note:** Console output screenshots will be added soon. Run `node registration.js` to see the test results.

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

## Prerequisites

- **Node.js**: version 12.0 or higher ([Download](https://nodejs.org/))
- **No external dependencies** - uses vanilla JavaScript

To check your Node.js version:
```bash
node --version
```

## Troubleshooting

### Common Issues

**Issue:** `node: command not found`

**Solution:** Install Node.js from [nodejs.org](https://nodejs.org/). Choose the LTS (Long Term Support) version.

---

**Issue:** Tests fail with "Student already registered"

**Solution:** This is expected behavior when testing duplicate prevention. The system correctly prevents duplicate email registrations.

---

**Issue:** Invalid email not being rejected

**Solution:** Ensure the email validation logic is working. Emails should contain '@' and domain. Check the validation method in the Student class.

---

**Issue:** Class syntax not recognized

**Solution:** You're using an old version of Node.js. Update to version 12+ which fully supports ES6 classes.

---

**Issue:** No output when running the script

**Solution:** Ensure you're running the correct file and that the console.log statements are present in the code.

For additional help, please open an issue in the repository issue tracker.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

### Enhancement Ideas
- Add more student properties (age, phone, address)
- Implement student removal functionality
- Add bootcamp capacity limits
- Create a GUI version with React or Vue
- Add database persistence (MongoDB, PostgreSQL)
- Implement search and filter functionality
- Add bootcamp completion tracking

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact & Support

- **Author**: José Santiago Echevarria
- **Issues**: Please report bugs via the repository issue tracker
- **Educational Context**: Demonstrates OOP in JavaScript, classes, validation, and testing
- **Learning Focus**: Class-based programming, data validation, duplicate prevention
