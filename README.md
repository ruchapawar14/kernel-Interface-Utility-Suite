# 🌐 Kernel Interface Utility Suite

> Custom Linux command utility suite developed using C Programming and native Linux system calls.

---

# 📌 Project Overview

The Kernel Interface Utility Suite is a Linux System Programming project that implements important Linux commands using low-level system calls instead of GNU utilities.

Commands are integrated with postfix **“x”** such as:

- `lsx`
- `pwdx`
- `cpx`
- `mvx`
- `catx`

This project demonstrates understanding of:

- Linux internals
- System calls
- File systems
- Process management
- File descriptor handling

---

# ✨ Features

- Custom Linux command implementation
- Native system call usage
- File handling operations
- Directory traversal
- Metadata management
- Linux permission handling
- Modular architecture
- Error handling and validation

---

# 🛠️ Commands Implemented

| Command | Description |
|---|---|
| `catx` | Display file contents |
| `cdx` | Change current directory |
| `cpx` | Copy files |
| `lsx` | List directory contents |
| `lsxopt` | List files with options |
| `mvx` | Move/Rename files |
| `pwdx` | Print working directory |
| `rmx` | Remove files |
| `statx` | Display file metadata |
| `statxperm` | Display file permissions |
| `touchx` | Create empty file |
| `unsmex` | Display system information |

---

# 🧩 System Calls Used

```c
open()
read()
write()
close()
stat()
unlink()
rename()
opendir()
readdir()
getcwd()
chdir()
uname()
```

---

# ⚙️ Compilation

```bash
gcc catx.c -o catx
gcc cdx.c -o cdx
gcc cpx.c -o cpx
gcc lsx.c -o lsx
gcc lsxopt.c -o lsxopt
gcc mvx.c -o mvx
gcc pwdx.c -o pwdx
gcc rmx.c -o rmx
gcc statx.c -o statx
gcc statxperm.c -o statxperm
gcc touchx.c -o touchx
gcc unsmex.c -o unsmex
```

---

# ▶️ Execution Examples

```bash
./catx demo.txt
./cpx source.txt destination.txt
./lsx
./lsxopt -i
./pwdx
./rmx demo.txt
./statx demo.txt
./touchx demo.txt
./unsmex
```

---

# 🎯 Learning Outcomes

- Understanding Linux system calls
- File descriptor management
- Directory and inode concepts
- Process handling
- Linux command implementation
- OS-level programming concepts

---

# 🖥️ Platform Requirement

- Ubuntu/Linux OS
- GCC Compiler

Install GCC:

```bash
sudo apt update
sudo apt install gcc
```

---

# 👩‍💻 Author

**Rucha Pawar**
