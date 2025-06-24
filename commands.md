Here's a **cleaned-up and organized version of your terminal history** with **duplicate commands removed**, and **descriptions added** for clarity. This version reflects a typical Git + file management workflow for DevOps practice:

---

### 🔧 **Initial Setup and File Operations**

```bash
mkdir git-for-devops               # Create project directory
cd git-for-devops                  # Enter the directory
pwd                                # Print working directory
vim hello.txt                      # Create and edit 'hello.txt'
cat hello.txt                      # View contents of 'hello.txt'
chmod 774 hello.txt                # Change permissions to rwxrwxr--
ls -l                              # List with file permissions
rm hello.txt                       # Remove the file
clear                              # Clear the terminal screen
```

---

### 🟢 **Initialize Git Repository**

```bash
git init                           # Initialize a new Git repository
ls -a                              # View hidden files (.git folder should be visible)
```

---

### 📝 **Working with Files Again**

```bash
touch devops.txt                   # Create a new file 'devops.txt'
vim devops.txt                     # Edit the file
```

---

### ✅ **Staging and Committing Changes**

```bash
git status                         # Check current git status
git add devops.txt                 # Stage the new file
git commit -m "added devops.txt"  # Commit the file with a message
```

---

### 🔄 **Restoring Deleted File**

```bash
rm devops.txt                      # Delete the file
git status                         # Check untracked/deleted files
git restore devops.txt             # Restore deleted file from last commit
```

---

### 🔧 **Git Configuration**

```bash
git config --global user.name "irahulgupta"                # Set global username
git config --global user.email "rahulgupta20795@gmail.com" # Set global email
```

---

### ✏️ **Make Further Changes and Commit**

```bash
vim devops.txt                     # Edit the file
git add .                          # Stage all changes
git commit -m "new changes"        # Commit updated content
```

---

### 🌿 **Working with Branches**

```bash
git branch                         # View current branches
git checkout -b dev                # Create and switch to 'dev' branch
git switch master                  # Switch back to 'master' branch
git switch dev                     # Switch again to 'dev'
```

---

### 📄 **More Edits in Dev Branch**

```bash
touch nibbu.txt                    # Create another file
git add .                          # Stage all files
git commit -m "added nibbu"        # Commit new file
```

---

### 📜 **View History**

```bash
git log                            # View detailed commit history
git log --oneline                  # View compact commit history
```

---

### 🧼 **Final Status Checks**

```bash
git status                         # Final check of current repo status
git remote -v                      # Check configured remote repositories
```

---

Let me know if you want me to export this as a `.sh` script or markdown summary!
