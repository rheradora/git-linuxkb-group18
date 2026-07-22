Command: `ps`

Description: Show snapshot of running processes.

Example: `ps aux`

---

Command: `top`

Description: Real-time process monitor. Press `q` to quit.

Example: `top`

---

Command: `lsof`

Description: List open files by process.

Example: `lsof -p 1234`

---

Command: `kill`

Description: Sends a signal (such as SIGTERM or SIGKILL) to terminate a running process using its Process ID (PID).

Example: `kill -9 1234`

---

Command: `htop`

Description: An interactive, visual process monitor that displays real-time CPU, memory, and running process information with scrollable navigation.

Example: `htop`

---

Command: `top -u`

Description: Launches the real-time process monitor filtered specifically to display only processes owned by a designated user.

Example: `top -u www-data`

---

Contributor: Jyia

Command: `pgrep`

Description: Searches for running processes by name and displays their Process IDs (PIDs).

Example: `pgrep nginx`


Command: `pstree`

Description: Displays running processes in a tree structure, showing the parent and child relationships of running processes.

Example: `pstree -p`


Command: `watch`

Description: Repeatedly executes a command at a specified interval, making it useful for continuously monitoring system activity.

Example: `watch -n 2 "ps aux"`

