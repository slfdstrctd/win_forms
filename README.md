# Windows Forms Course Project

This repository contains coursework for a comprehensive Windows Forms development course, spanning two semesters with progressively advanced topics and practical applications.

## 📚 Course Overview

The course is structured into two semesters:
- **Semester 1**: Fundamentals of Windows Forms with C# (.NET Core 3.1)
- **Semester 2**: Advanced topics with C++/CLI and complex applications

## 🗂️ Project Structure

```
win_forms-3/
├── semester_1/          # Basic Windows Forms applications (C#)
│   ├── WinFormsApp2/    # Currency Converter
│   ├── WinFormsApp3/    # Stopwatch
│   ├── WinFormsApp4/    # Timer Application
│   ├── WinFormsApp5/    # Photo Viewer
│   ├── WinFormsApp6/    # Window Blinds Effect
│   ├── WinFormsApp7/    # Pounds Converter
│   ├── WinFormsApp8/    # Calculator
│   ├── WinFormsApp9/    # Car Application
│   └── WinFormsApp10/   # Final Exam Project
└── semester_2/          # Advanced applications (C++/CLI)
    ├── lesson1/         # GSL Mathematical Functions
    ├── lesson2/         # Advanced UI Components
    ├── lesson3/         # Data Visualization
    ├── lesson4/         # Graphics Programming
    ├── lesson5/         # Diagrams and Charts
    ├── lesson6/         # Database Integration
    ├── lesson7/         # Network Programming
    ├── lesson8/         # Multimedia Applications
    ├── lesson9/         # Advanced Graphics
    ├── lesson10/        # System Integration
    ├── lesson11/        # Performance Optimization
    ├── lines/           # Line Drawing Application
    └── game_2048/       # 2048 Game Implementation
```

## 🎯 Semester 1 - C# Windows Forms Fundamentals

### Technologies Used
- **Framework**: .NET Core 3.1
- **Language**: C# 
- **UI Framework**: Windows Forms
- **Target Platform**: Windows

### Applications Developed

| App # | Name | Description | Key Features |
|-------|------|-------------|--------------|
| 2 | **Currency Converter** | Simple currency conversion tool | Input validation, real-time calculation |
| 3 | **Stopwatch** | Digital stopwatch application | Timer control, start/stop/reset functionality |
| 4 | **Timer** | Countdown timer application | Custom timer intervals, alerts |
| 5 | **Photo Viewer** | Image viewing application | File dialogs, image display |
| 6 | **Window Blinds** | Window blinds animation effect | Animation, visual effects |
| 7 | **Pounds Converter** | Weight conversion utility | Unit conversion, input validation |
| 8 | **Calculator** | Basic arithmetic calculator | Mathematical operations, UI design |
| 9 | **Car Application** | Vehicle management system | Data management, forms |
| 10 | **Final Exam** | Comprehensive application | Integration of learned concepts |

### Key Learning Objectives
- Windows Forms controls and events
- User input validation
- Timer and animation basics
- File operations and dialogs
- Basic UI/UX principles
- Event-driven programming

## 🚀 Semester 2 - Advanced C++/CLI Applications

### Technologies Used
- **Framework**: .NET Framework 4.7.2
- **Language**: C++/CLI (Managed C++)
- **Libraries**: GSL (GNU Scientific Library)
- **Graphics**: GDI+, Custom drawing
- **Platform**: Windows (Visual Studio 2019)

### Advanced Projects

#### Mathematical Computing (Lesson 1)
- Integration with GSL (GNU Scientific Library)
- Scientific calculations and mathematical functions
- Bessel functions and advanced mathematics

#### Graphics and Visualization (Lessons 2-5)
- **Lines Application**: Advanced line drawing and geometric algorithms
- **Diagrams**: Chart creation and data visualization
- **Multi-diagrams**: Complex chart combinations
- Custom graphics rendering

#### Game Development (Final Project)
- **2048 Game**: Complete implementation of the popular 2048 puzzle game
- Features:
  - 4x4 grid gameplay
  - Smooth animations
  - Score tracking
  - Game over detection
  - Restart functionality
  - Color-coded tiles
  - Keyboard controls (Arrow keys)

### Advanced Topics Covered
- C++/CLI mixed-mode programming
- Scientific computing integration
- Advanced graphics programming
- Game development principles
- Performance optimization
- Memory management
- Complex UI interactions

## 🛠️ Setup and Installation

### Prerequisites
- **Semester 1**: Visual Studio 2019+ with .NET Core 3.1
- **Semester 2**: Visual Studio 2019+ with C++/CLI support
- **For GSL projects**: GNU Scientific Library installation
- Windows 10 or later

### Running the Applications

#### Semester 1 (C# Applications)
```bash
cd semester_1/WinFormsApp[X]/WinFormsApp[X]
dotnet run
```

Or use the pre-built executables:
```
WinFormsApp*/WinFormsApp*/bin/Debug/netcoreapp3.1-windows/WinFormsApp*.exe
```

#### Semester 2 (C++/CLI Applications)
Open the solution files (`.sln`) in Visual Studio and build/run the projects.

## 🎮 Featured Application: 2048 Game

The 2048 game represents the culmination of the course, demonstrating:

### Game Features
- **Grid-based gameplay**: 4x4 tile grid
- **Tile merging**: Combine tiles with same values
- **Smooth animations**: Fluid tile movements
- **Dynamic coloring**: Color-coded tiles based on values
- **Score system**: Real-time score tracking
- **Game states**: Win/lose detection and restart option

### Technical Implementation
- **Object-oriented design**: Clean separation of game logic and UI
- **Event handling**: Keyboard input processing
- **Graphics programming**: Custom tile rendering and animations
- **Game loop**: Efficient game state management
- **Memory management**: Proper resource cleanup

### Controls
- **Arrow Keys**: Move tiles in respective directions
- **Game Logic**: Tiles slide and merge when moved
- **Objective**: Reach the 2048 tile to win

## 📖 Learning Progression

### Beginner Level (Apps 2-4)
- Basic form design and controls
- Event handling fundamentals
- Simple calculations and validations

### Intermediate Level (Apps 5-7)
- File operations and dialogs
- Advanced UI effects and animations
- Data conversion and formatting

### Advanced Level (Apps 8-10)
- Complex application logic
- Multiple form management
- Integration of various concepts

### Expert Level (Semester 2)
- Mixed-mode programming (C++/CLI)
- Scientific computing integration
- Advanced graphics and game development
- Performance-critical applications

## 🔧 Development Environment

### Recommended IDE Settings
- **Visual Studio 2019** or later
- **Extensions**: 
  - C++/CLI support
  - .NET Core development tools
  - Windows Forms designer

### Project Configuration
- **Semester 1**: .NET Core 3.1 Windows Forms projects
- **Semester 2**: C++/CLI projects with .NET Framework 4.7.2

## 📝 Notes

- All applications are designed for Windows platform
- Semester 1 focuses on C# and managed code
- Semester 2 introduces native/managed interop with C++/CLI
- The progression shows evolution from simple forms to complex applications
- Each project builds upon concepts learned in previous lessons