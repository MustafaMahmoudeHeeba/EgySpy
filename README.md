## GitHub Team Rules

### 1. Create a Branch for Each Task

Do not work directly on `main`.

Create a branch for your task:

```bash
git checkout -b <task-name>
```

Example:

```bash
git checkout -b use-case-diagram
```

### 2. Commit Your Work

After finishing your task:

```bash
git add .
git commit -m "Add <task-name>"
```

Examples:

```bash
git commit -m "Add project proposal"
git commit -m "Add use case diagram"
git commit -m "Add literature review"
```

### 3. Push Your Branch

```bash
git push -u origin <branch-name>
```

### 4. Create a Pull Request

Create a Pull Request from your branch to `main`.

Another team member should quickly review it before merging.

### 5. Keep Files Organized

Put each task in its appropriate folder under `docs/`.

```text
docs/
├── project-planning/
├── literature-review/
├── requirements/
└── system-design/
```

### 6. Task Workflow

```text
Task
 ↓
Create Branch
 ↓
Do the Work
 ↓
Commit
 ↓
Push
 ↓
Pull Request
 ↓
Review & Merge
```

**Important:** Do not push directly to `main`.
