# NS2 Network Simulation Using Ping Agents

This project simulates a simple wired network using **NS2 (Network Simulator 2)** with three interconnected nodes and demonstrates the transmission of ping messages. It captures and analyzes the **Round Trip Time (RTT)** between nodes to evaluate network latency and communication performance.

## 📌 Project Description

- Simulated a **3-node wired network topology** using duplex links.
- Implemented `Agent/Ping` to simulate the transmission of ping packets between nodes.
- Measured **Round Trip Time (RTT)** — the time for packets to travel from the source node to the destination and back.
- Used **Tcl scripting** to define the simulation flow, schedule events, and control agent behavior.
- Generated:
  - `.tr` file for trace-level analysis
  - `.nam` file for graphical animation using **NAM** (Network Animator)
- Demonstrated core concepts in:
  - Event-driven simulation
  - Agent-based packet exchange
  - Network latency measurement

## 📂 Files Included

| File Name     | Description                                 |
|---------------|---------------------------------------------|
| `prog4.tcl`   | Main Tcl simulation script                  |
| `prog4.tr`    | Trace file with simulation output           |
| `prog4.nam`   | NAM animation file for visualizing topology |

> Run the simulation to generate `.tr` and `.nam` automatically.

## 🧪 How to Run

1. **Install NS2** (on Ubuntu):

   ```bash
   sudo apt update
   sudo apt install ns2 nam
Run the simulation:

bash
Copy
Edit
ns prog4.tcl
View the network animation:

bash
Copy
Edit
nam prog4.nam
📈 Output
Terminal will display ping replies and RTT values.

The prog4.nam file will animate the packet flow between nodes.

The prog4.tr file can be parsed for deeper network analysis (e.g., throughput, drops, etc.).

🧠 Key Concepts
RTT (Round Trip Time): A critical metric that indicates the delay in network communication, important for evaluating performance.

Agent/Ping: Used in NS2 to mimic ICMP ping behavior.

Duplex Links: Full-duplex wired connections used between nodes.

🛠️ Technologies Used
NS2 (Network Simulator 2)

Tcl Scripting Language

NAM (Network Animator)

Ubuntu Linux

👨‍💻 Author
Prajwal BV
Department of ECE, NMIT-Bengaluru
Course: Computer Networks and Applications (22ECG61)

