# 🚀 Server Stats Monitoring Script

A lightweight Bash script to analyze basic server performance statistics on any Linux machine.

---

## 📌 Features

* ✅ CPU Usage (percentage)
* ✅ Memory Usage (used / total + percentage)
* ✅ Disk Usage (root partition)
* ✅ Uptime (human-readable)
* ✅ Top 5 processes by CPU usage
* ✅ Top 5 processes by Memory usage

---

## 🖥️ Preview

```
============= SERVER STATS =============
Uptime: 2 hours, 15 minutes

CPU Usage: 23.5%
Memory Usage: 61.2% (3200MB / 8000MB)
Disk Usage: 45%

========================================
Top 5 CPU Processes:
...

========================================
Top 5 Memory Processes:
...
```

---

## ⚙️ Requirements

* Linux OS (Ubuntu, Debian, CentOS, etc.)
* Bash shell
* Common tools:

  * `top`
  * `free`
  * `df`
  * `ps`
  * `awk`
  * `sed`

> 💡 Most Linux systems already include these tools.

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/sarawutms/server-performance-stats.git
cd server-performance-stats
```

Make the script executable:

```bash
chmod +x server-stats.sh
```

---

## ▶️ Usage

Run the script:

```bash
./server-stats.sh
```

---

## 🧠 How It Works

The script collects system data using standard Linux commands:

* `top` → CPU usage
* `free` → memory stats
* `df` → disk usage
* `ps` → running processes
* `uptime` → system uptime

Data is processed using `awk` and `sed` for formatting.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Developed by **Sarawut**

---

## ⭐ Support

If you find this useful, consider giving it a ⭐ on GitHub!
