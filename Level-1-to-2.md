# Bandit Level 1  → Level 2

## 🎯 Level Goal

Find the password for the next level stored in a file called `-` in the home directory.

## 📌 Given Information

* Host: `bandit.labs.overthewire.org`
* Port: `2220`
* Username: `bandit1`
* Password: `[Password found in the previous level]`

## 🧠 Approach 

1. Connect to the Bandit server using SSH.
2. List the files in the home directory.
3. Read the contents of the `-` file to obtain the password.

## 💻 Commands Used

```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
ls
cat ./-
```

## 📝 Explanation

- Used the `ssh` command to connect to the remote Bandit server using the provided username and port.
- Ran the `ls` command to list files in the home directory.
- Used the `cat` command to display the contents of the `-` file directly in the terminal.

## 🔑 Password Found

⚠️ Password intentionally omitted to preserve the challenge.

## 🧠 Key Takeaway

* Basic Linux commands like `ls` and `cat`
* Basic understanding of `dashed filename`
* Understanding of file reading in Linux
