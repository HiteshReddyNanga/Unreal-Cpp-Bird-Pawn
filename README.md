# 🐦 Bird Pawn — Unreal Engine C++

A small Unreal Engine C++ gameplay programming project created while learning and practicing **C++ with Unreal Engine**.

The project focuses on building a custom Bird Pawn in C++ and implementing player-controlled movement using Unreal Engine's **Enhanced Input System**.

---

## 🎥 Demo

### Bird Flight Demo

The demo showcases the Bird Pawn responding to player input and flying through the Unreal Engine environment.

> **Demo video:** ![Bird Pawn Demo](Media/BirdPawn_Demo.mp4)

---

## ✨ Features & Implementation

### 🐦 Custom Bird Pawn

Created a custom Pawn class in C++:

```cpp
ABird : public APawn
```

The Bird Pawn handles its own component setup, movement functionality, input configuration, and gameplay logic through Unreal Engine C++.

### 🎮 Enhanced Input System

Implemented player input using Unreal Engine's **Enhanced Input System**.

The project works with Unreal's modern input framework, including:

- `UInputMappingContext`
- `UInputAction`
- `UEnhancedInputComponent`
- `UEnhancedInputLocalPlayerSubsystem`

Input is bound to C++ functions to control the Bird Pawn.

### 🧩 Component-Based Setup

The Bird Pawn uses several Unreal Engine components:

| Component | Purpose |
|---|---|
| `UCapsuleComponent` | Collision |
| `USkeletalMeshComponent` | Bird character mesh |
| `UFloatingPawnMovement` | Pawn movement |
| `USpringArmComponent` | Camera positioning |
| `UCameraComponent` | Player camera |

### 💻 C++ Gameplay Programming

This project provided hands-on practice with:

- C++ classes and inheritance
- Header (`.h`) and source (`.cpp`) files
- Unreal Engine constructors
- Member variables and functions
- Unreal Engine macros
- Component creation and attachment
- Input binding
- Pointers and Unreal Engine object references
- Working with Unreal Engine APIs

---

## 🛠️ Technologies

- **Unreal Engine 5.8**
- **C++**
- **Enhanced Input System**
- **Visual Studio**

---

## 📂 Repository Structure

```text
Unreal-Cpp-Bird-Pawn/
│
├── BirdPawn/
│   ├── Bird.h
│   └── Bird.cpp
│
└── README.md
```

### `Bird.h`

Contains the Bird Pawn class declaration, component references, variables, and function declarations.

### `Bird.cpp`

Contains the implementation of the Bird Pawn, including component initialization, input setup, and movement logic.

---

## 🎯 Project Goals

The main goal of this project is to learn Unreal Engine C++ through practical implementation rather than theory alone.

This project focuses on understanding how C++ gameplay classes interact with Unreal Engine's component system and Enhanced Input framework.

---

## 🚀 Future Improvements

As I continue learning Unreal Engine C++, I plan to explore:

- More advanced flight movement
- Takeoff and landing mechanics
- Flying animations
- Improved camera controls
- Additional gameplay interactions
- More advanced movement systems
- Integration of C++ systems with Blueprints

---

## 📚 Learning Journey

This Bird Pawn is one of my first practical Unreal Engine C++ projects.

I am building small gameplay systems step by step to develop a stronger foundation in **C++ gameplay programming** and eventually apply these concepts to larger Unreal Engine projects.

---

**More Unreal Engine C++ projects coming soon. 🎮**
