# Common Linux commands

Frequently used Linux commands with brief descriptions and examples.

---

## 1. `ls`
Lists files and directories in the current directory.

```bash
ls
ls -l       # Long listing format
ls -a       # Show hidden files
```

---

## 2. `cd`
Changes the current working directory.

```bash
cd /home/user/Documents
cd ..        # Move up one directory
```

---

## 3. `pwd`
Prints the current working directory.

```bash
pwd
```

---

## 4. `cp`
Copies files or directories.

```bash
cp file1.txt file2.txt
cp -r dir1/ dir2/   # Copy a directory recursively
```

---

## 5. `mv`
Moves or renames files or directories.

```bash
mv oldname.txt newname.txt   # Rename file
mv file.txt /home/user/      # Move file to another directory
```

---

## 6. `rm`
Removes files or directories.

```bash
rm file.txt
rm -r dir1/   # Remove a directory recursively
```

Caution: deleted files cannot be easily recovered.

---

## 7. `touch`
Creates an empty file or updates the timestamp of an existing file.

```bash
touch newfile.txt
```

---

## 8. `mkdir`
Creates a new directory.

```bash
mkdir new_folder
mkdir -p parent/child  # Create parent and child directories
```

---

## 9. `cat`
Displays the contents of a file, concatenates files, or creates files.

```bash
cat file.txt
cat file1.txt file2.txt > combined.txt
```

---

## 10. `man`
Displays the manual pages (documentation) for a command.

```bash
man ls
man mkdir
```

---

### Quick reference

| Command | Description |
|---------|-------------|
| `ls` | List directory contents |
| `cd` | Change directory |
| `pwd` | Show current directory path |
| `cp` | Copy files or directories |
| `mv` | Move or rename files/directories |
| `rm` | Remove files or directories |
| `touch` | Create empty files |
| `mkdir` | Create directories |
| `cat` | View or concatenate files |
| `man` | Show command manual |
