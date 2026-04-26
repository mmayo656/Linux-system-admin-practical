# System Monitoring and Performance Analysis

## Objective
Identify system performance metrics and diagnose potential bottlenecks.

## Tools Used
- top
- vmstat
- iostat
- dmesg

## Actions Performed

### 1. CPU and Process Monitoring
Used `top` to observe running processes and CPU utilization.

![top](../screenshots/05-monitoring/top.png)

**Finding:**
- System idle > 90%
- No CPU bottleneck detected

---

### 2. Disk I/O Analysis
Used `iostat` to analyze disk performance.

![iostat](../screenshots/05-monitoring/iostat.png)

**Finding:**
- Minimal disk activity
- No I/O wait issues

---

### 3. Memory Usage
Used `vmstat` to evaluate memory utilization.

![vmstat](../screenshots/05-monitoring/vmstat.png)

**Finding:**
- No swap usage
- Healthy memory availability

---

## Result

The system is operating efficiently with no CPU, memory, or disk bottlenecks.
