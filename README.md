
# Raspberry Pi Embedded C++ Project Using GitHub

## Aim
To manage a Raspberry Pi embedded C++ project using GitHub by cloning, modifying, committing, and synchronizing source files.

## Procedure

### Step 1: Create a Repository
1. Open GitHub and sign in.
2. Click **New Repository**.
3. Enter the repository name `RaspberryPi-Embedded-Cpp`.
4. Click **Create Repository**.

### Step 2: Clone the Repository
Download the repository to the local system.

```bash
git clone https://github.com/username/RaspberryPi-Embedded-Cpp.git
```

Navigate to the project folder.

```bash
cd RaspberryPi-Embedded-Cpp
```

### Step 3: Modify Source Files
Create or edit the C++ source file.

```bash
nano main.cpp
```

Write the program, save the file, and exit.

### Step 4: Check Changes
Check the modified files.

```bash
git status
```

### Step 5: Stage Changes
Add the modified files to the staging area.

```bash
git add .
```

### Step 6: Commit Changes
Save the changes in Git history.

```bash
git commit -m "Updated embedded C++ program"
```

### Step 7: Push Changes
Upload the committed changes to GitHub.

```bash
git push origin main
```

### Step 8: Pull Latest Changes
Download the latest updates from GitHub.

```bash
git pull origin main
```

## Workflow

Clone → Modify → Stage → Commit → Push → Pull

## Result
Thus, the Raspberry Pi embedded C++ project was successfully managed and synchronized with GitHub using Git version control.
