# C++17 Project

A modern C++17+ project scaffolding with CMake build system.

## Prerequisites

- CMake 3.20 or higher
- C++17 compatible compiler (GCC 7+, Clang 5+, MSVC 2017+)

## Build Instructions

### Create build directory
```bash
mkdir build && cd build
```

### Configure the project
```bash
cmake ..
```

### Build the project
```bash
cmake --build .
```

### Run the executable
```bash
./bin/cpp_project
```

### Run tests
```bash
ctest
# or
./bin/test_runner
```

## Project Structure

```
.
├── CMakeLists.txt       # Root CMake configuration
├── include/             # Header files
│   └── app.h
├── src/                 # Source files
│   ├── main.cpp
│   └── app.cpp
└── tests/               # Test files
    ├── CMakeLists.txt
    └── test_main.cpp
```

## Features

- C++17 standard enforced
- CMake build system (3.20+)
- Organized directory structure
- Header/source separation
- Basic test framework setup
- .gitignore configured

## Customization

Edit `CMakeLists.txt` to:
- Change project name
- Add external dependencies
- Configure additional compiler flags
- Set up more complex build targets
# cpp-repo
