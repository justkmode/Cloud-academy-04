# Cloud-academy-04
Week 4 - Linux and Bash - 🚀 Exercise - Creating Files

This exercise will guide you through creating and editing a file on a Linux system using both `nano` and `vi/vim` editors.

---

### Task 1: Create a New File

**Objective:** Create a file named `class_notes.txt` in your home directory.

1. **Create the file:**
    
    ```bash
    touch ~/class_notes.txt
    
    ```
    
2. **Verify the file creation:**
    
    ```bash
    ls -l ~/class_notes.txt
    
    ```
    

---

### Task 2: Edit the File with `nano`

**Objective:** Open `class_notes.txt` with `nano` and add your name and today's date.

1. **Open the file with `nano`:**
    
    ```bash
    nano ~/class_notes.txt
    
    ```
    
2. **In `nano`, add your name and today's date at the top of the file. Feel free to add a few lines about what you've learned so far.**
3. **Save your changes with `nano`:**
    - Press `Ctrl + O` to save the file.
    - Press `Enter` to confirm.
    - Press `Ctrl + X` to exit `nano`.

---

### Task 3: Edit the File with `vi/vim` (Optional)

**Objective:** Open `class_notes.txt` with `vi` or `vim` and add your name and today's date.

1. **Open the file with `vi` or `vim`:**
    
    ```bash
    vi ~/class_notes.txt
    
    ```
    
2. **Enter insert mode by pressing `i`.**
3. **Add your name and today's date at the top of the file. Feel free to add a few lines about what you've learned so far.**
4. **Save your changes and exit `vi/vim`:**
    - Press `Esc` to return to normal mode.
    - Type `:wq` and press `Enter` to save and exit.

---

### Task 4: Verify the Changes

**Objective:** Confirm that your changes have been saved correctly.

1. **Display the contents of `class_notes.txt`:**
    
    ```bash
    cat ~/class_notes.txt
    
    ```
    

---

By following these steps, you will practice creating and editing files using two different text editors, which is an essential skill for managing files on a Unix-like operating system.
