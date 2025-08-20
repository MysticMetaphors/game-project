# Contributing Guidelines

To keep our workflow smooth and consistent, please follow these steps when making changes.

## Workflow

### 1. Fork & Clone

Clone the repository locally:

```bash
git clone https://github.com/MysticMetaphors/game-project
cd game-project
```

### 2. Create a Branch

Always create a new branch for your changes.  
Use a descriptive name (e.g., `feature/entity-jump`, `fix/animation-bug`):

```bash
git checkout -b feature/<short-description>
```

### 3. Make Your Changes

- Implement your feature, fix, or improvement.
- Keep commits small and meaningful.
- Write clear commit messages:

```bash
git commit -m "Add jump functionality to Entity base class"
```

### 4. Push Your Branch

Push your branch to your fork:

```bash
git push origin feature/<short-description>
```

### 5. Open a Pull Request (PR)

- Go to the main repository on GitHub.
- Open a Pull Request from your branch.

### 6. Review & Approval

- Wait for at least one reviewer to check your code.
- Make requested changes if needed.
- Once approved, your branch will be merged into `main`.
