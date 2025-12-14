# Bandit Level 4  → Level 5

## 🎯 Level Goal

Find the password for the next level stored in a human readable, non executable file in the `inhere` directory.

## 📌 Given Information

* Host: `bandit.labs.overthewire.org`
* Port: `2220`
* Username: `bandit4`
* Password: `[Password found in the previous level]`

## 🧠 Approach 

1. Connect to the Bandit server using SSH.
2. List the files in the home directory.
3. View inside `inhere` directory
4. find the humanreadble file 
5. Read the contents of the file to obtain the password.

## 💻 Commands Used

```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
ls
cd inhere
ls -la
find ./*
cat /-file07 
```

## 📝 Explanation

- Used the `ssh` command to connect to the remote Bandit server using the provided username and port.
- Ran the `ls` command to list files in the home directory.
- Changed into the `inhere` directory using `cd inhere`
- Ran the `ls -la` to list all files, in the `inhere` directory.
- Ran the `find ./*` to find the file type of the files
- Used the `cat` command to display the contents of the `-file07` file directly in the terminal.

## 🔑 Password Found

⚠️ Password intentionally omitted to preserve the challenge.

## 🧠 Key Takeaway

* Basic Linux commands like `ls` , 'cd` , `find` and `cat`
* Basic understanding of `file types` and directories
* Understanding of file reading in Linux

## 📝 Notes

* find method can be used to display the file type of the files
