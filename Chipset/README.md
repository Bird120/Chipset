# Digital Chipset Simulator

🚀 **Digital Chipset Simulator**  
A high-performance, modular simulator for digital logic circuits built with modern C++20. This project demonstrates advanced C++ concepts such as the Singleton pattern, smart pointers, constexpr optimizations, and robust error handling.

## Key Features

- **Singleton Pattern**  
  Ensures a single instance of the system to centralize circuit management.

- **Smart Pointer Management**  
  Uses `std::unique_ptr` for safe and efficient memory management.

- **Compile-Time Optimizations**  
  Leverages `constexpr` for certain calculations to enhance performance.

- **Robust Exception Handling**  
  Implements structured error handling to ensure simulation reliability.

- **Implementation of Logic Components**  
  OR and AND components are implemented using polymorphism for a flexible and scalable simulation.

## Technologies Used

- **Language:** C++20
- **Key Concepts:** Singleton, Smart Pointers (`std::unique_ptr`), `constexpr`, RAII, Polymorphism
- **Build Tools:** Makefile
- **Version Control:** Git

## Installation & Execution

### 1. Clone the Repository

```bash
git clone https://github.com/Bird120/Chipset.git
cd chipset
```

```bash
g++ -o simulator main.cpp -std=c++20 -pthread
```

execute 
```bash
./chipset file.nts
```


digital-chipset-simulator/
├── Chipset/                # Contains logic components (AND, OR, etc.) (in progress)
│   ├── ANDGate.cpp         # AND gate implementation (4081) (in progress)
│   ├── ORGate.cpp          # OR gate implementation (4071) (in progress)
│   └── ANDGate.cpp         # AND gate implementation (4081) (in progress)
├── Error/                  # Structured Exception handling classes
├── System/                 # System management and Singleton implementation
├── fileParser/             # File parsing and input processing
├── include/                # Header files for the project
├── main.cpp                # Program entry point
├── Makefile                # Makefile for building the project
└── README.md               # Project documentation (this file)

