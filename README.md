# Concurrent Queue in C++

This is a simple C++ project that demonstrates a concurrent queue. A concurrent queue allows multiple threads to safely push and pop elements from a shared queue, ensuring thread safety and synchronization.

## Features

- Thread-safe push and pop operations.
- Uses a mutex and condition variable for synchronization.
- Provides an example of a producer-consumer scenario using two threads.

## Getting Started

To compile and run the project, you can use the steps given below:

1. **Install a C++ Compiler:**
   Ensure that you have a C++ compiler like g++ installed on your system. If not, you can install it following your system's package manager instructions.

2. **Compile the Code:**
   Navigate to the directory where the `main.cpp` file is located and compile the code using the following command:

   `g++ -std=c++11 main.cpp -o concurrent_queue`

3. **Run the Executable:**
    Execute the generated `concurrent_queue` executable by running the following command:

    `./concurrent_queue.exe`

4. **Observe the Output:**
The program will execute, demonstrating the producer-consumer pattern with two threads. You'll see numbers produced and consumed.