# Calculator Clone Using Java

A desktop calculator project built with **Java Swing**.  
This project demonstrates core GUI development concepts such as frames, text fields, buttons, and action listeners.

## Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Current Features](#current-features)
- [Current Status](#current-status)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Overview

This repository contains a simple calculator UI built from scratch using Java Swing components.

The app currently includes:

- A calculator window (`JFrame`)
- A display input field (`JTextField`)
- Number buttons (`0-9`)
- Operator buttons (`+`, `-`, `*`, `/`)
- `=` and `C` buttons in the layout

It is a great starting point for learning event-driven GUI programming in Java.

## Tech Stack

- **Language:** Java
- **GUI Toolkit:** Swing (`javax.swing`)
- **Event Handling:** `ActionListener`
- **Build/Run:** `javac` and `java` (no external dependencies)

## Project Structure

```text
CalculatorCloneUsingJava/
├── Calculator.java
├── Calculator.class
└── README.md
```

## Current Features

- Responsive desktop window layout (fixed absolute positioning)
- Clickable numeric buttons that append values to the display
- Basic calculator keypad design

## Current Status

The project UI is implemented and launches successfully.

At this stage, numeric input is wired, but full arithmetic behavior is not yet connected in code (operators, equals, and clear actions are present in the interface and ready for logic wiring).

## Getting Started

### Prerequisites

Make sure Java is installed:

- JDK 8+ recommended
- Verify installation:

```bash
java -version
javac -version
```

### Run Locally

1. Clone this repository:

```bash
git clone https://github.com/<your-username>/CalculatorCloneUsingJava.git
cd CalculatorCloneUsingJava
```

2. Compile the source file:

```bash
javac Calculator.java
```

3. Run the app:

```bash
java Calculator
```

## Usage

1. Launch the application.
2. Click number buttons to enter values in the display.
3. Use this project as a base to implement full calculator functionality.

## Screenshots

Add your screenshots in a folder like `assets/` and embed them below:

```md
![Calculator UI](assets/calculator-ui.png)
```

## Roadmap

- Connect operation buttons (`+`, `-`, `*`, `/`) to logic
- Implement `=` to evaluate expressions
- Implement `C` to clear input
- Add decimal support (`.`)
- Add error handling (for example division by zero)
- Refactor repetitive listeners into reusable methods
- Improve UI design and keyboard input support

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch:

```bash
git checkout -b feature/your-feature-name
```

3. Commit your changes:

```bash
git commit -m "Add: your feature description"
```

4. Push to your branch:

```bash
git push origin feature/your-feature-name
```

5. Open a Pull Request

## License

This project is currently unlicensed.

If you want to make it open source, consider adding an MIT License file.

## Author

Created by **MSI**.
