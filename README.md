# Linux Support Lab

This lab demonstrates basic Linux troubleshooting tasks commonly performed by Tier-1 IT support technicians.

The goal is to show familiarity with Linux command-line diagnostics used to identify system and network issues.

---

# Tools Used

Linux terminal

Commands demonstrated:

- uname
- df
- top
- ping

---

# 1. System Information

Command used:

uname -a

Purpose:

Displays system kernel version and operating system details.

Helpdesk use case:

Used to verify system version when diagnosing compatibility issues.

Screenshot:

![system](screenshots/system-info.png)

---

# 2. Disk Usage

Command used:

df -h

Purpose:

Displays disk space usage for all mounted drives.

Helpdesk use case:

Used to identify storage issues or full disks affecting system performance.

Screenshot:

![disk](screenshots/disk-usage.png)

---

# 3. Process Monitoring

Command used:

top

Purpose:

Shows active processes and system resource usage.

Helpdesk use case:

Used to detect processes consuming excessive CPU or memory.

Screenshot:

![process](screenshots/process-check.png)

---

# 4. Network Connectivity

Command used:

ping -c 4 google.com

Purpose:

Tests network connectivity to an external host.

Helpdesk use case:

Used to verify internet access and troubleshoot network connectivity.

Screenshot:

![network](screenshots/network-test.png)

---

# Skills Demonstrated

- Linux command-line troubleshooting
- System diagnostics
- Disk usage analysis
- Network connectivity testing
