# CPU Scheduling & Memory Management Visualization 🚀

This project is a **Java-based GUI application** that visualizes **CPU Scheduling (Round Robin) and Best-Fit Memory Allocation** using **Swing and Java concurrency**. It provides a dynamic and interactive way to understand how processes are scheduled and how memory is allocated in an operating system.

## 🌟 Features
- **Round Robin Scheduling**: Implements **preemptive scheduling** with time slices.
- **Best-Fit Memory Allocation**: Efficient memory management using the **best-fit** strategy.
- **Process Visualization**: Displays process states (**NEW, RUNNING, TERMINATED**) dynamically.
- **Memory Usage Representation**: Graphically updates available and allocated memory blocks.
- **Multi-threaded Execution**: Uses Java concurrency (`ExecutorService`, `Thread`) for scheduling.
- **GUI with Swing**: Interactive user interface for adding and monitoring processes.

## 📦 Dependencies
- **Java Swing**: UI components (`JFrame`, `JPanel`, `JLabel`, `JProgressBar`, etc.)
- **Java Concurrency Utilities**: (`ExecutorService`, `TimeUnit`, `ScheduledExecutorService`)
- **Data Structures**: (`Queue`, `LinkedList`, `Set`, `HashSet`)

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/cpu-scheduling-visualization.git
cd cpu-scheduling-visualization
```

### 2️⃣ Compile and Run
```bash
javac Main.java
java Main
```

## 🔄 Usage Guide
1. **Launch the application**: Runs a GUI with process and memory panels.
2. **Add processes**: Simulates processes with priority, arrival time, burst time, and memory requirements.
3. **Watch execution**: Processes execute in **Round Robin** order, updating progress bars and states dynamically.
4. **Observe memory allocation**: Best-fit memory allocation strategy updates UI with current memory blocks.

## 🎯 Why This Project is Unique?
- **Educational Tool**: Helps students & developers visualize OS concepts.
- **Fully Interactive**: Unlike theoretical simulators, this provides a **real-time** view.
- **Multi-Threaded Simulation**: Uses **Java concurrency** to mimic real-world scheduling.

## 🔄 Contributing
### 1️⃣ Fork the Project
Click on the **Fork** button to create your own copy.

### 2️⃣ Clone Your Fork
```bash
git clone https://github.com/your-username/cpu-scheduling-visualization.git
cd cpu-scheduling-visualization
```

### 3️⃣ Create a Branch
```bash
git checkout -b feature-new-scheduling-algorithm
```

### 4️⃣ Make Changes & Commit
Modify the code, then commit your changes.
```bash
git add .
git commit -m "Added new scheduling algorithm"
```

### 5️⃣ Push & Create a Pull Request
```bash
git push origin feature-new-scheduling-algorithm
```
Go to the original repository and open a **Pull Request**.

## 📜 License
This project is licensed under the MIT License.

---
🚀 **Explore, learn, and contribute to CPU scheduling visualization!** 🚀