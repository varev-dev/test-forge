# Test Forge
## Introduction
[Test Forge](https://github.com/varev-dev/test-forge) is an desktop application designed to simplify the process of creating tests for C++ developers. Using the Google Test framework, this application provides a comprehensive suite of tools to the creation and execution of various types of unit tests.

The development of [Test Forge](https://github.com/varev-dev/test-forge) will follow a gradual roadmap.
1. The initial phase focuses on a local version, enabling users to manage projects and generate tests directly on their computers.
2. Subsequent phases will introduce integration with an external database and server for centralized project management.
3. Ultimately, the project aims to deliver a fully-featured web application and enhanced desktop version, unifying all functionalities.

## Features
- **Project Management**: Create and organize projects, track history and changes.
- **Structure Mapping**: Automatically process and map source code into an intuitive data.
- **Test Management**: Create, customize, organize unit tests for specified components. 
- **Report Generation**: Generate detailed reports, summarizing test results and coverage.
- **Project Migration**: Export and import projects while preserving data and assets.

## Technologies Used
- **Qt**: Cross-platform framework for building the graphical user interface.
- **Google Test**: Framework for writing and executing unit tests in C++.
- **Conan**: Dependency manager for handling external libraries.
- **C++17**: Programming language standard used for the application.

## Build & Run
```bash
# Clone repository
git clone https://github.com/varev-dev/test-forge.git
cd test-forge

# Create build directory
mkdir build && cd build

# Install dependencies
pip install conan
conan install . --build=missing

# Configure and build
cmake ..
cmake --build .

# Run application
./test-forge
```

## Contact

For questions or support, feel free to open an issue on GitHub or contact the project maintainer via email at For questions or support, feel free to open an issue on GitHub or contact the project maintainer via email at [doga.kacper@gmail.com](mailto:doga.kacper@gmail.com).


