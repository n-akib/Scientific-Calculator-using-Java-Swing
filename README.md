# Scientific Calculator using Java Swing

A comprehensive scientific calculator application built with Java Swing that provides both basic arithmetic operations and advanced mathematical functions. This desktop application features a user-friendly graphical interface with a complete set of scientific computing capabilities.

## 🚀 Features

### Basic Operations
- **Arithmetic Operations**: Addition (+), Subtraction (-), Multiplication (×), Division (÷)
- **Decimal Support**: Floating-point calculations with decimal precision
- **Clear Functions**: Clear (C) and All Clear (AC) operations
- **Backspace**: Delete last entered digit
- **Memory Functions**: Memory store, recall, and clear operations

### Scientific Functions
- **Trigonometric Functions**: sin, cos, tan, asin, acos, atan
- **Logarithmic Functions**: log (base 10), ln (natural logarithm)
- **Exponential Functions**: e^x, x^y (power), x² (square), x³ (cube)
- **Root Functions**: √x (square root), ∛x (cube root), x^(1/y) (nth root)
- **Mathematical Constants**: π (pi), e (Euler's number)
- **Factorial**: n! calculation
- **Percentage**: % operations

### Advanced Features
- **Parentheses Support**: Complex expression evaluation with () brackets
- **Degree/Radian Toggle**: Switch between angle units for trigonometric functions
- **Scientific Notation**: Display results in scientific notation for large/small numbers
- **Error Handling**: Proper error messages for invalid operations
- **Keyboard Support**: Full keyboard input support
- **Responsive UI**: Clean and intuitive interface design

## 🛠️ Technologies Used

- **Java SE** - Core programming language
- **Java Swing** - GUI framework for desktop application
- **AWT** - Abstract Window Toolkit for UI components
- **Math Library** - Java's built-in mathematical functions
- **Event Handling** - ActionListener for button interactions

## 📋 Prerequisites

- **Java Development Kit (JDK)** 8 or higher
- **Java Runtime Environment (JRE)** for running the application
- Any Java IDE (IntelliJ IDEA, Eclipse, NetBeans) for development

## 🔧 Installation & Setup

### Option 1: Running from Source Code

1. **Clone the repository**:
   ```bash
   git clone https://github.com/n-akib/Scientific-Calculator-using-Java-Swing.git
   cd Scientific-Calculator-using-Java-Swing
   ```

2. **Compile the Java files**:
   ```bash
   javac *.java
   ```

3. **Run the application**:
   ```bash
   java MainCalculator
   ```

### Option 2: Using IDE

1. **Import the project** into your preferred Java IDE
2. **Build the project** using IDE's build tools
3. **Run the main class** to start the calculator

### Option 3: Creating Executable JAR

```bash
# Compile all Java files
javac *.java

# Create JAR file
jar cfm ScientificCalculator.jar MANIFEST.MF *.class

# Run the JAR file
java -jar ScientificCalculator.jar
```

## 🎮 How to Use

### Basic Calculations
1. **Launch the application**
2. **Enter numbers** using the number buttons (0-9)
3. **Select operation** (+, -, ×, ÷)
4. **Enter second number**
5. **Press equals (=)** to get the result

### Scientific Functions
1. **Enter a number**
2. **Click on scientific function** (sin, cos, log, etc.)
3. **Result is displayed** immediately

### Advanced Operations
1. **Use parentheses** for complex expressions: (2+3)×4
2. **Toggle Deg/Rad** for trigonometric functions
3. **Use memory functions** to store and recall values
4. **Clear operations** using C (clear) or AC (all clear)

## 🏗️ Project Structure

```
Scientific-Calculator-using-Java-Swing/
├── src/
│   ├── ScientificCalculator.java      # Main calculator class
│   ├── CalculatorGUI.java             # GUI implementation
│   ├── MathOperations.java            # Mathematical calculations
│   └── ButtonHandlers.java            # Event handling
├── resources/
│   ├── icons/                         # Button icons (optional)
│   └── styles/                        # UI styling (optional)
├── README.md
└── MANIFEST.MF                        # JAR manifest file
```

## 🖥️ User Interface

### Layout Components
- **Display Screen**: Shows current input and calculation results
- **Number Pad**: Digits 0-9 for numeric input
- **Basic Operations**: +, -, ×, ÷, =, C, AC
- **Scientific Panel**: Trigonometric, logarithmic, and exponential functions
- **Memory Panel**: M+, M-, MR, MC for memory operations
- **Mode Toggle**: Degree/Radian selector for trigonometric functions

### Visual Design
- **Clean Layout**: Organized button arrangement for easy navigation
- **Color Coding**: Different colors for different function types
- **Responsive Design**: Proper spacing and button sizing
- **Clear Display**: Easy-to-read LCD-style display screen

## 🧮 Mathematical Operations

### Basic Arithmetic
```java
// Addition: 5 + 3 = 8
// Subtraction: 10 - 4 = 6
// Multiplication: 7 × 8 = 56
// Division: 15 ÷ 3 = 5
```

### Scientific Functions
```java
// Trigonometric: sin(30°) = 0.5
// Logarithmic: log(100) = 2
// Exponential: 2^3 = 8
// Square Root: √16 = 4
// Factorial: 5! = 120
```

### Complex Expressions
```java
// Example: (2 + 3) × sin(45°) = 3.535
// Example: log(100) + √25 = 2 + 5 = 7
```

## 🔧 Key Features Implementation

### Error Handling
- **Division by Zero**: Displays "Error" for invalid operations
- **Invalid Input**: Handles incorrect mathematical expressions
- **Overflow Protection**: Manages very large number calculations
- **Domain Errors**: Handles functions outside their valid domain

### Memory Functions
- **Memory Store (MS)**: Saves current display value
- **Memory Recall (MR)**: Retrieves stored value
- **Memory Clear (MC)**: Clears stored memory
- **Memory Add (M+)**: Adds current value to memory

### Keyboard Support
- **Numbers**: 0-9 keys for digit input
- **Operations**: +, -, *, / for basic arithmetic
- **Enter**: Equals function
- **Escape**: Clear current input
- **Backspace**: Delete last digit

## 🧪 Testing

### Manual Testing
1. **Test basic operations** with various number combinations
2. **Verify scientific functions** with known mathematical values
3. **Check error handling** with invalid inputs
4. **Test memory functions** for proper storage and retrieval
5. **Validate keyboard input** functionality

### Test Cases
```java
// Basic Operations
assert calculate("5 + 3") == 8;
assert calculate("10 - 4") == 6;
assert calculate("7 * 8") == 56;
assert calculate("15 / 3") == 5;

// Scientific Functions
assert calculate("sin(30)") == 0.5; // in degrees
assert calculate("log(100)") == 2;
assert calculate("sqrt(16)") == 4;
```

## 🚀 Future Enhancements

- **Graphing Capabilities**: Add function plotting features
- **History Function**: Store and recall previous calculations
- **Themes**: Multiple UI themes (dark mode, light mode)
- **Unit Conversion**: Built-in unit converter
- **Complex Numbers**: Support for complex number operations
- **Equation Solver**: Solve algebraic equations
- **Statistical Functions**: Mean, median, standard deviation
- **Programming Mode**: Binary, octal, hexadecimal operations

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**n-akib** - [GitHub Profile](https://github.com/n-akib)

## 🙏 Acknowledgments

- Java Swing documentation and tutorials
- Mathematical function implementations
- Open source calculator projects for inspiration
- Java community for continuous support

## 📞 Support

If you encounter any issues or have questions:
1. Check the existing issues on GitHub
2. Create a new issue with detailed description
3. Provide screenshots if UI-related problems occur

---

**Calculate with precision and style! 🧮✨**