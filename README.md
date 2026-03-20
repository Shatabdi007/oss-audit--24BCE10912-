# oss-audit-24mim10091

## Student Details

Name: SAMRIDHI TYAGI 
Roll Number: 224MIM10091
Course: Open Source Software


## Chosen Software
**Python Programming Language**

Python is an open-source programming language known for its simplicity and readability. It is widely used in web development, data science, automation, and artificial intelligence.


##  Project Contents

* script1.sh → System Identity Report
* script2.sh → FOSS Package Inspector
* script3.sh → Disk and Permission Auditor
* script4.sh → Log File Analyzer
* script5.sh → Manifesto Generator


##  Dependencies

Make sure the following are installed on your Linux system:

* python3
* lsb-release
* coreutils (usually pre-installed)
* dpkg (for package checking)

Install missing packages using:

```
sudo apt update
sudo apt install python3 lsb-release
```

---

## How to Run Scripts (Step-by-Step)

### Step 1: Give Execution Permission

```
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
```

---

### Script 1 — System Identity Report

**Command:**

```
./script1.sh
```

**Description:**
This script displays system information such as kernel version, current user, uptime, date, and Linux distribution.

---

###  Script 2 — FOSS Package Inspector

**Command:**

```
./script2.sh python3
```

Description:
This script checks whether a package is installed on the system. It also prints a short description of the package using a case statement.



###  Script 3 — Disk and Permission Auditor

Command:

```
./script3.sh
```

Description:
This script checks important system directories and displays their size and permission details.


### Script 4 — Log File Analyzer

Command:

```
./script4.sh /var/log/syslog error
```

Description:
This script reads a log file and counts how many times a specific keyword (default: “error”) appears.



###  Script 5 — Manifesto Generator

Command:

```
./script5.sh
```

Description:
This script takes user input and generates a text file containing a simple open-source manifesto.


##  Notes

* All scripts were tested on a Linux system (Ubuntu-based).
* Make sure you provide correct file paths while running Script 4.
* Use `cat manifesto.txt` to view output of Script 5.



## Conclusion

This project helped in understanding both the theoretical and practical aspects of open-source software. It also improved my knowledge of Linux commands and shell scripting.
