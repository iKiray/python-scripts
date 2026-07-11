# Project: File Renamer

## Objective

Create a Python script that renames files in a specified folder.

Do **not** worry about making it perfect on the first try. Focus on understanding each step before moving to the next.

---

## Step 1: Define the Goal

Before writing any code, decide:

- What files should be renamed?
- Should the script rename every file in one folder?
- Should subfolders be included?
- What should the new filenames look like?

Example ideas:

```text
photo001.jpg
photo002.jpg
photo003.jpg
```

or

```text
Vacation-001.jpg
Vacation-002.jpg
Vacation-003.jpg
```

---

## Step 2: Plan the Workflow

Write the logic in plain English before coding.

Example workflow:

```text
1. Ask for the folder path.
2. Get a list of files.
3. Loop through each file.
4. Generate a new filename.
5. Rename the file.
```

---

## Step 3: Research the Standard Library

Find the Python modules that can:

- Work with folders
- List files
- Rename files
- Join file paths safely

Do not copy a complete solution—learn what each function does.

---

## Step 4: List the Files

Your first milestone is simply printing every filename.

Ask yourself:

- How do I access a folder?
- How do I retrieve every file inside it?
- How do I ignore folders if necessary?

Expected milestone:

```text
IMG_0001.jpg
IMG_0002.jpg
IMG_0003.jpg
```

---

## Step 5: Loop Through the Files

Once you have the list, process each file one at a time.

Practice:

- Using a `for` loop
- Accessing the current filename
- Printing each filename

---

## Step 6: Build New Filenames

Determine how each new name will be created.

Think about:

- Keeping the original file extension
- Creating sequential numbers
- Formatting numbers with leading zeros

Example:

```text
Old:
IMG_1234.jpg

New:
Vacation-001.jpg
```

---

## Step 7: Rename the File

Once you have:

- The original filename
- The new filename

Research the function that renames one file into another.

Remember:

- It needs the original path.
- It needs the destination path.

---

## Step 8: Test Safely

Before actually renaming files:

Print the changes instead.

Example:

```text
Old: IMG_1234.jpg
New: Vacation-001.jpg
```

Once everything looks correct, replace the print statement with the rename function.

---

# Stretch Goals

After completing the basic version, consider adding:

- Ignore directories
- Ignore hidden files
- Let the user choose a filename prefix
- Let the user choose the starting number
- Preview mode
- Undo log
- Error handling
- Rename only certain file extensions
- Sort files before renaming
- Command-line arguments

---

# Concepts Practiced

- Variables
- Strings
- Lists
- Loops
- Functions
- File paths
- Standard library modules
- Basic file operations
- String formatting

---

# Milestones

- [ ] Ask the user for a folder path
- [ ] List every file
- [ ] Loop through each file
- [ ] Generate new filenames
- [ ] Preview the changes
- [ ] Rename the files
- [ ] Test on a sample folder
- [ ] Add one stretch goal
