Documentation Outline:
1. Project Overview
Description: This project simulates memory management in a healthcare setting where ECG signals are processed in real-time. It demonstrates both manual and automatic memory management in C++.
Objective: Showcase effective memory handling for real-time patient data processing using C++.
2. Classes and Code Explanation
PatientData: Handles dynamic memory allocation for patient ECG data.
MemoryManager: Manages memory, showcasing both manual and smart pointer memory management.
ECGProcessor: Processes ECG signals using basic signal processing algorithms.
3. Memory Management Techniques
Manual Memory Management: Use of new and delete.
Smart Pointers: std::shared_ptr to automate memory management.
Memory Leak Simulation: Deliberately leak memory to demonstrate the risks of poor memory management.
4. Real-World Application
The simulator can be expanded into real-world healthcare systems where data is streamed in real-time, such as IoT-connected medical devices. Efficient memory management is essential for ensuring the reliability and scalability of such systems.
5. Benchmarks & Testing
Demonstrate the system's efficiency by comparing manual memory management with smart pointers.
Use tools like Valgrind to detect memory leaks and optimize memory allocation.
