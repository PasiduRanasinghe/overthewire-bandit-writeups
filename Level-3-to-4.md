# Bandit Level 3  → Level 4

## 🎯 Level Goal

Find the password for the next level stored in a hidden file in the `inhere` directory.

## 📌 Given Information

* Host: `bandit.labs.overthewire.org`
* Port: `2220`
* Username: `bandit3`
* Password: `[Password found in the previous level]`

## 🧠 Approach 

1. Connect to the Bandit server using SSH.
2. List the files in the home directory.
3. View inside `inhere` directory
3. Read the contents of the hidden file to obtain the password.

## 💻 Commands Used

```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
ls
cd inhere
ls -la
cat ...Hiding-From-You
```

## 📝 Explanation

- Used the `ssh` command to connect to the remote Bandit server using the provided username and port.
- Ran the `ls` command to list files in the home directory.
- Changed into the `inhere` directory using `cd inhere`
- Ran the `ls -la` to list all files, including hidden ones, in the `inhere` directory.
- Used the `cat` command to display the contents of the `...Hiding-From-You` file directly in the terminal.

## 🔑 Password Found

⚠️ Password intentionally omitted to preserve the challenge.

## 🧠 Key Takeaway

* Basic Linux commands like `ls` , 'cd` and `cat`
* Basic understanding of `hidden files` and directories
* Understanding of file reading in Linux

## 📝 Notes

* Hidden files in Linux start with a dot (`.`), so `ls -la` is required to reveal them.
