# Bandit Level 0 → Level 1

## 🎯 Level Goal

Find the password for the next level stored in the `readme` file.

## 📌 Given Information

* Host: `bandit.labs.overthewire.org`
* Port: `2220`
* Username: `bandit0`
* Password: `bandit0`

## 🧠 Approach 

1. Connect to the Bandit server using SSH.
2. List the files in the home directory.
3. Read the contents of the `readme` file to obtain the password.

## 💻 Commands Used

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat readme
```

## 📝 Explanation

- Used the `ssh` command to connect to the remote Bandit server using the provided username and port.
- Ran the `ls` command to list files in the home directory.
- Used the `cat` command to display the contents of the `readme` file directly in the terminal.

## 🔑 Password Found

⚠️ Password intentionally omitted to preserve the challenge.

## 🧠 Key Takeaway

* How to use SSH to log in to a remote server
* Basic Linux commands like `ls` and `cat`
* Understanding of file reading in Linux
