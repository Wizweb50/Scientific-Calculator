# SciCalc 🧮

**SciCalc** is a modern Android scientific calculator built with **Kotlin** and **Jetpack Compose**. It provides a clean and easy-to-use Standard calculator by default, with a Scientific mode for advanced mathematical calculations.

The project focuses on **correct calculations, clean architecture, and a simple user experience**.

## ✨ Features

### Standard Mode

* Basic arithmetic operations
* Addition, subtraction, multiplication, and division
* Percentages
* Decimal numbers
* Positive/negative numbers
* Parentheses
* Backspace and clear
* Operator precedence

### Scientific Mode

* Trigonometric functions: `sin`, `cos`, `tan`
* Inverse trigonometric functions: `asin`, `acos`, `atan`
* Logarithms: `log`, `ln`
* Powers: `x²`, `xʸ`, `10ˣ`, `eˣ`
* Square root
* Factorial
* Reciprocal
* Mathematical constants: `π`, `e`
* DEG/RAD angle modes
* Implicit multiplication such as `2π` and `5sin(30)`

## 🧠 Calculation Engine

SciCalc uses a dedicated expression evaluation engine with:

* Operator precedence
* Nested parentheses
* Shunting-yard expression parsing
* RPN-based evaluation
* Implicit multiplication
* Mathematical error handling
* Floating-point precision handling
* Domain and overflow validation

## 🎨 UI & UX

* Jetpack Compose + Material 3
* Clean and responsive calculator interface
* Standard mode as the default
* Organized Scientific mode
* Light and dark themes
* Large touch-friendly buttons
* Horizontal scrolling for long expressions
* Accessibility-friendly controls
* Haptic feedback

## 🏗️ Architecture

The application separates the main responsibilities into:

* **CalculatorEngine** — expression parsing and mathematical evaluation
* **CalculatorViewModel** — calculator state and user interactions
* **CalculatorUiState** — UI state representation
* **Compose UI** — calculator interface and components
* **Unit Tests** — verification of calculation logic

This separation keeps the calculation logic independent from the UI and makes the project easier to maintain and test.

## 🧪 Testing

The project includes unit tests covering:

* Basic arithmetic
* Operator precedence
* Parentheses
* Scientific functions
* DEG/RAD calculations
* Powers and roots
* Factorials
* Invalid expressions
* Division by zero
* Mathematical domain errors
* Overflow
* Floating-point precision

## 🛠️ Tech Stack

* **Kotlin**
* **Jetpack Compose**
* **Material 3**
* **Android SDK**
* **Android Studio**
* **JUnit**

## 📱 Requirements

* Android Studio
* Android SDK
* A compatible Android device or emulator

## 🚀 Getting Started

1. Clone the repository.
2. Open the project in Android Studio.
3. Allow Gradle to sync.
4. Connect an Android device or start an emulator.
5. Run the application.

## 📌 Project Status

SciCalc is a functional scientific calculator project with Standard and Scientific modes, a dedicated calculation engine, comprehensive error handling, and unit testing.

## 👨‍💻 Author

**Muhammad Mohsin Khan**

BS Software Engineering Student
Aspiring Machine Learning Engineer
