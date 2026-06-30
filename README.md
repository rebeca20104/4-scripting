# 4-scripting

This repository contains two simple programs:

* **hello.sh** – A Bash script
* **hello.py** – A Python script

Both programs take a name as a command-line argument and print:

```text
Hello <name>, right now the time is <current date and time based on timezone>
```

---

## Repository Structure

```text
4-scripting/
├── hello.sh
├── hello.py
└── README.md
```

---

# Bash Script

**File:** `hello.sh`

## Is Bash interpreted or compiled?

Bash is an **interpreted** scripting language. The Bash interpreter reads and executes the script line by line. It is not compiled into a standalone executable before running.

## Make the script executable

```bash
chmod +x hello.sh
```

## Run the Bash script

```bash
./hello.sh Rebecca
```

### Example Output

```text
Hello Rebecca, right now the time is Tue Jun 30 11:25:15 IST 2026
```

---

# Python Script

**File:** `hello.py`

## Is Python interpreted or compiled?

Python is an **interpreted** programming language. The Python interpreter executes the script (internally compiling it to bytecode before running it).

## Run the Python script

```bash
python3 hello.py Rebecca
```

### Example Output

```text
Hello Rebecca, right now the time is 2026-06-30 11:25:15.124318+05:30
```

---

# Requirements

* Bash script accepts a name as a command-line argument.
* Python script accepts a name as a command-line argument.
* Both programs display the current date and time using the system's local timezone.
