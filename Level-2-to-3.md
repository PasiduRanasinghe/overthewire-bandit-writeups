# Bandit Level 2  → Level 3

## 🎯 Level Goal

Find the password for the next level stored in a file called `--spaces in this filename--` in the home directory.

## 📌 Given Information

* Host: `bandit.labs.overthewire.org`
* Port: `2220`
* Username: `bandit2`
* Password: `[Password found in the previous level]`

## 🧠 Approach 

1. Connect to the Bandit server using SSH.
2. List the files in the home directory.
3. Read the contents of the `--spaces in this filename--` file to obtain the password.

## 💻 Commands Used

```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
ls
cat './--spaces in this filename--'
```

## 📝 Explanation

- Used the `ssh` command to connect to the remote Bandit server using the provided username and port.
- Ran the `ls` command to list files in the home directory.
- Used the `cat` command to display the contents of the `--spaces in this filename--` file directly in the terminal.

## 🔑 Password Found

⚠️ Password intentionally omitted to preserve the challenge.

## 🧠 Key Takeaway

* Basic Linux commands like `ls` and `cat`
* Basic understanding of `dashed filename` and `spaces in filenames`
* Understanding of file reading in Linux
