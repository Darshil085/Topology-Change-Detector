# 🚀 Topology Change Detector

## 📌 Project Overview

Topology Change Detector is a Computer Networks project that detects dynamic changes in network topology using Mininet simulation and Python visualization.

The project monitors link changes such as addition or removal of connections between nodes and updates the topology accordingly.

---

## 🎯 Objective

* Detect changes in network topology dynamically
* Monitor switch/link events
* Update topology map
* Display topology changes
* Maintain simple log updates

---

## 🛠️ Technologies Used

* 🐍 Python
* 🌐 Mininet
* 📊 NetworkX
* 📈 Matplotlib

---

## ⚙️ How It Works

1. Creates an initial network topology
2. Displays nodes and links in graph format
3. Simulates topology changes:

   * Link Added
   * Link Removed
4. Updates graph after every change
5. Logs topology updates in terminal / file

---

## ▶️ How to Run

### Run Python Visualization

```bash
python3 topology_detector.py
```

### Run Mininet Simulation

```bash
sudo mn --topo single,3
```

### Test Connectivity

```bash
pingall
```

### Simulate Link Failure

```bash
link s1 h3 down
```

### Restore Link

```bash
link s1 h3 up
```

---

## 📸 Output

* Initial topology graph
* Updated topology after link addition
* Updated topology after link removal
* Connectivity results using `pingall`

---

## 💡 Sample Results

* Normal State → `0% dropped`
* Link Failure → `66% dropped`
* Restored State → `0% dropped`

---

## 📚 Learning Outcomes

* Understanding of network topology
* Network simulation using Mininet
* Dynamic link failure testing
* Graph-based visualization using Python

---

## 🔮 Future Scope

* Real-time network monitoring
* GUI dashboard
* Alert system for failures
* SDN controller integration

---

## 👨‍💻 Author

Darshil085

---

⭐ A simple and effective project for understanding dynamic network topology changes.
