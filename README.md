# 🚀 Advanced IPC Debugger & Visualization

An interactive **Operating System (OS) based visualization tool** for simulating and debugging **Inter-Process Communication (IPC)** mechanisms with real-time animations, process monitoring, deadlock detection, and system logging.

This project provides an intuitive and visual representation of how processes communicate using **Pipes**, **Message Queues**, and **Shared Memory**, while also demonstrating **deadlock analysis using resource allocation graphs**.

---

## 📌 Project Overview

The **Advanced IPC Debugger & Visualization** project is designed to help students and developers understand the internal working of **Inter-Process Communication (IPC)** mechanisms in Operating Systems.

The application visually simulates communication between processes and provides a debugging environment with:

* Process monitoring
* IPC mechanism simulation
* Deadlock detection
* Resource graph visualization
* Real-time system logs
* Process state management

This project is especially useful for **Operating Systems (OS)** concepts, academic demonstrations, and practical visualization of IPC communication models.

---

## 🎯 Objectives

The main objectives of this project are:

* Visualize **Inter-Process Communication**
* Simulate communication between multiple processes
* Demonstrate **Pipe**, **Message Queue**, and **Shared Memory**
* Detect and visualize **Deadlocks**
* Provide **real-time system monitoring**
* Improve understanding of **Operating System concepts**

---

## ✨ Features

### 🔄 IPC Mechanism Simulation

The system simulates three major IPC communication methods:

### 1️⃣ Pipe Communication

Simulates communication between:

```text
Process P1 ↔ Pipe ↔ Process P2
```

Features:

* Data transfer simulation
* Process state updates
* Animated communication flow
* Event logging

---

### 2️⃣ Message Queue Communication

Simulates:

```text
Process P3 ↔ Message Queue ↔ Process P4
```

Features:

* Message enqueue and dequeue simulation
* Queue-based communication visualization
* Status tracking

---

### 3️⃣ Shared Memory Communication

Simulates:

```text
Process P5 ↔ Shared Memory ↔ Process P6
```

Features:

* Shared memory writing and reading
* Memory synchronization visualization
* Process execution state monitoring

---

## ⚠️ Deadlock Detection System

The project includes an **advanced deadlock detection mechanism** using a **Resource Allocation Graph (RAG)** approach.

The system:

* Traverses process-resource relationships
* Detects cyclic dependencies
* Identifies deadlocks
* Displays deadlock paths visually

### Deadlock Detection Logic

The algorithm checks for cycles in the graph using:

```text
Depth First Search (DFS)
```

If a cycle exists:

```text
⚠️ Deadlock Detected!
```

Otherwise:

```text
✅ No Deadlock Detected
```

Example deadlock cycle:

```text
p5 → memory → p6 → p5
```

---

## 🖥️ System Interface

The project contains:

### ✅ Interactive Process Visualization

* 6 simulated processes
* Real-time status changes
* Animated IPC interactions

### ✅ Dynamic Process States

Processes can switch between:

```text
Ready
Running
Waiting
```

### ✅ Animated Communication

* Visual highlighting
* Process pulsing effects
* Connection flow animation

### ✅ Real-Time Logging

System logs include:

* Pipe communication logs
* Queue message transfer logs
* Shared memory operations
* Deadlock notifications
* System reset logs

### ✅ Statistics Dashboard

Tracks:

* Total Processes
* IPC Mechanisms
* Messages Sent
* Deadlocks Detected

### ✅ Process Details Modal

Displays:

* Process ID (PID)
* Status
* Memory Usage
* IPC Mechanism Used

### ✅ Tab-Based Process Monitoring

Individual tabs for:

```text
P1, P2, P3, P4, P5, P6
```

---

## 🏗️ System Architecture

```text
+------------------------------+
|      Advanced IPC Debugger   |
+------------------------------+
               |
      -------------------
      |        |        |
   Pipe     Queue   Shared Memory
      |        |        |
    P1↔P2    P3↔P4    P5↔P6
               |
        Deadlock Detection
               |
        Resource Graph (DFS)
```

---

## 🧠 Concepts Implemented

This project demonstrates several important **Operating System** concepts:

### 🔹 Inter Process Communication (IPC)

* Pipe
* Message Queue
* Shared Memory

### 🔹 Deadlock Detection

* Resource Allocation Graph
* Cycle Detection
* DFS Algorithm

### 🔹 Process Management

* Process states
* Execution flow
* Synchronization

### 🔹 System Monitoring

* Logs
* Statistics
* Runtime updates

---

## 🛠️ Tech Stack

### Frontend

* **HTML5**
* **CSS3**
* **JavaScript (Vanilla JS)**

### Design

* Responsive UI
* CSS Animations
* Dark Theme Dashboard

### Algorithms

* **Depth First Search (DFS)** for Deadlock Detection

---

## 📂 Project Structure

```text
IPC-Debugger-Visualization/
│── ipc.html
│── README.md
```

---

## ⚙️ How It Works

### Step 1: Select Simulation

Choose one of:

* Simulate Pipe
* Simulate Queue
* Simulate Memory

---

### Step 2: Process Communication

The selected IPC mechanism starts communication between processes.

Example:

```text
P1 → Pipe → P2
```

---

### Step 3: Real-Time Logging

Logs are generated instantly.

Example:

```text
[PIPE] Process P1 sending data to pipe...
[PIPE] Data received by Process P2
```

---

### Step 4: Deadlock Detection

Click:

```text
Check Deadlock
```

The system analyzes the resource graph and detects cycles.

---

### Step 5: Process Monitoring

Click:

```text
Process Details
```

to inspect process information.

---

## 🚀 Installation & Setup

### Clone Repository

```bash
git clone https://github.com/your-username/IPC-Debugger-Visualization.git
```

### Open Project

Open the folder in:

* VS Code
* IntelliJ IDEA
* Sublime Text

### Run Project

Simply open:

```text
ipc.html
```

in your browser.

No installation or dependencies required.

---

## 📸 Screenshots

Add screenshots here for better project presentation.

Example:

```text
screenshots/
│── dashboard.png
│── deadlock-detection.png
│── process-monitor.png
```

Then include:

```md
![Dashboard](screenshots/dashboard.png)
![Deadlock Detection](screenshots/deadlock-detection.png)
```

---

## 🔮 Future Enhancements

Future improvements may include:

* Real OS-level IPC integration
* Socket communication simulation
* Semaphore visualization
* Producer-Consumer simulation
* CPU Scheduling integration
* Multi-threading visualization
* Performance analytics dashboard
* Export logs feature
* IPC performance benchmarking

---

## 🎓 Academic Relevance

This project is highly useful for:

### Subjects:

* Operating System
* System Programming
* Computer Architecture
* Process Synchronization

### Suitable For:

* **B.Tech CSE Major/Mini Project**
* **BCA/MCA Projects**
* **Operating System Lab Demonstration**
* **Academic Presentation**

---

## 💡 Learning Outcomes

After using this project, users can understand:

* How IPC works internally
* Process communication flow
* Deadlock detection techniques
* Resource allocation concepts
* Real-time process monitoring

---

## 👨‍💻 Author

**Sangam Kumar**
B.Tech Computer Science & Engineering

GitHub:
https://github.com/kumarSangam100

---

## 📜 License

This project is developed for **educational and learning purposes**.

---

## ⭐ Support

If you found this project useful:

⭐ Star the repository
🍴 Fork the project
🛠️ Contribute improvements
