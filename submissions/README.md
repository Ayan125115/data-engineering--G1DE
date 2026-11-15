# Student Homework Submissions

This folder contains homework solutions submitted by G1DE students.

Every student must maintain their own folder and submit completed assignments through GitHub Pull Requests.

## 1. Folder Structure

Use your GitHub username as your folder name.

```text
submissions/
└── YOUR_GITHUB_USERNAME/
    ├── python/
    │   ├── HW-01/
    │   │   └── solution.py
    │   └── HW-02/
    │       └── solution.py
    │
    ├── sql/
    └── pyspark/
```

## 2. Submission Rules

1. Fork the official G1DE repository.
2. Clone your fork to your laptop.
3. Create a separate branch for each homework assignment.
4. Write your solution inside your assigned student folder.
5. Do not modify class materials or other students' folders.
6. Commit and push your changes.
7. Create a Pull Request against the official G1DE repository.

## 3. Git Workflow

### Clone your fork

```bash
git clone https://github.com/YOUR_USERNAME/data-engineering-G1DE.git
cd data-engineering-G1DE
```

### Connect the official repository

```bash
git remote add upstream https://github.com/INSTRUCTOR_USERNAME/data-engineering-G1DE.git
```

### Create a homework branch

```bash
git checkout -b YOUR_USERNAME/HW-01
```

### Add your solution

```bash
mkdir -p submissions/YOUR_USERNAME/python/HW-01
```

Save your solution as `solution.py` inside this folder.

### Commit and push

```bash
git add submissions/YOUR_USERNAME/python/HW-01/solution.py
git commit -m "Submit Python HW-01"
git push -u origin YOUR_USERNAME/HW-01
```

## 4. Pull Request

Create a Pull Request on GitHub with:

- Base repository: Official G1DE repository
- Base branch: main
- Head repository: Your fork
- Compare branch: Your homework branch

Include the homework number in the Pull Request title.

Example:

`HW-01 Submission - YOUR_USERNAME`

## 5. Important Guidelines

- Submit your own work.
- Follow the specified folder and file naming conventions.
- Keep code readable and properly formatted.
- Test your code before submission.
- Do not modify or delete existing class materials.
- Address instructor feedback when requested.

**Happy Learning!**