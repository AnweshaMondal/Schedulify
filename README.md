
### **📌 Schedulify** 🚀  
*A Java-based CPU Scheduling Simulator featuring FCFS & Preemptive SJF algorithms using linked lists.*  

---

## **📖 Overview**  
This project implements two fundamental **CPU Scheduling Algorithms** in Java:  
1. **First-Come, First-Served (FCFS)** – A non-preemptive scheduling method where processes are executed in the order they arrive.  
2. **Preemptive Shortest Job First (SJF)** – A dynamic scheduling algorithm where the process with the shortest remaining time gets CPU priority.  

💡 Ideal for students, developers, and OS enthusiasts who want to **understand CPU scheduling** through hands-on simulation.  

---

## **📌 Features**  
✅ **FCFS Algorithm** – Simple, non-preemptive execution.  
✅ **Preemptive SJF Algorithm** – Shortest remaining time first (SRTF) with dynamic preemption.  
✅ **Linked List Implementation** – Efficient process storage and management.  
✅ **Interactive User Input** – Enter the number of processes, their IDs, burst times, and arrival times.  
✅ **Detailed Output** – Displays waiting time, turnaround time, and average statistics.  

---

## **🚀 Installation & Usage**  

### **📥 Prerequisites**  
Ensure you have **Java** installed on your system.  
Check by running:  
```sh
java -version
```

### **🔧 Steps to Run**  
1️⃣ **Clone the Repository**  
```sh
git clone [https://github.com/AnweshaMondal/Schedulify.git]
cd Schedulify
```
  
2️⃣ **Compile the Java files**  
```sh
javac FCFS.java PreemptiveSJf.java
```

3️⃣ **Run the Programs**  
- **FCFS Scheduling**  
  ```sh
  java FCFSLinkedList
  ```
- **Preemptive SJF Scheduling**  
  ```sh
  java SJFPreemptiveLinkedList
  ```

4️⃣ **Enter the Process Details**  
Example input for both programs:  
```
Enter the number of processes: 3
Enter process ID, arrival time, and burst time for each process:
1 0 5
2 1 3
3 2 8
```

---

## **📊 Sample Output**  
### **FCFS Example Output**  
```
Process ID  Burst Time  Waiting Time  TurnAround Time  Arrival
1           5          0            5               0
2           11         5            16              0
3           11         16           27              0
Avg. waiting time= 7.000000
Avg. turnaround time= 16.000000
```

### **Preemptive SJF Example Output**  
```
Process ID  Arrival Time  Burst Time  Waiting Time  Turnaround Time
1           0            8          7            15
2           1            4          0            4
3           2            9          8            17
Avg. waiting time = 5.000000
Avg. turnaround time = 12.000000
```

---
  

📢 **Contributions are welcome!** Feel free to fork, improve, and submit a PR.  

---

### **👨‍💻 Author**  
👤 **Anwesha Mondal**  
