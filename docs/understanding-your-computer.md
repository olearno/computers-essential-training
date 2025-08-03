# Understanding Your Computer

Learn about your operating system, RAM, storage, and how to monitor your computer’s resources.

## What You Will Learn

- How to check your OS, RAM, and storage
- How to monitor system resources
- Tools to get more information

## Try It Yourself

Spend up to one hour exploring your computer. Try the following exercises and commands:

### 1. Find Basic System Information

- **Windows:**  
  - Open "System Information" (type it in the Start menu).
  - Run `systeminfo` in Command Prompt.
- **Mac:**  
  - Click the Apple menu > "About This Mac".
- **Linux:**  
  - Run `uname -a` and `free -h` in the terminal.

Write down your OS name, version, RAM, and processor details.

---

### 2. Check Storage (ROM) and Disk Space

- **Windows:**  
  - Open "This PC" and note the total and free space on your drives.
  - Run `wmic logicaldisk get size,freespace,caption` in Command Prompt.
- **Mac:**  
  - Click Apple menu > "About This Mac" > "Storage".
- **Linux:**  
  - Run `df -h` in the terminal.

List your total and available storage.

---

### 3. Monitor System Resources

- **Windows:**  
  - Open Task Manager (Ctrl+Shift+Esc) and look at CPU, Memory, and Disk usage.
- **Mac:**  
  - Open "Activity Monitor" (find it in Applications > Utilities).
- **Linux:**  
  - Run `top` or `htop` in the terminal.

Take a screenshot or note down the current usage.

---

### 4. Explore Device Manager / System Profiler

- **Windows:**  
  - Open "Device Manager" (search in Start menu).
- **Mac:**  
  - Open "System Information" (hold Option and click Apple menu).
- **Linux:**  
  - Run `lshw` or `lscpu` in the terminal (may require `sudo`).

List any interesting hardware details you find.

---

### 5. Bonus: Find Your Computer’s Name and Network Info

- **Windows:**  
  - Run `hostname` and `ipconfig` in Command Prompt.
- **Mac/Linux:**  
  - Run `hostname` and `ifconfig` or `ip a` in the terminal.

Write down your computer’s name and IP address.

---

**Reflection:**  
Write a short summary of what you discovered about your computer. Did you find anything surprising?