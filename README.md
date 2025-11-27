# Rivet
[Rivet](https://rivet.design/) is a visual AI editor for product designers. Use Rivet's style editor and chat to make changes, and then publish generated production code to your repository.

### Quickstart:

```bash
npm install -g rivet-design
```

**For web applications:**

- Navigate to your project repo
- Start your project's local development server
- Run `rivet` in your project directory which will spin up an interactive frontend you can use to make changes

```bash
cd my-project-repo
rivet
```

### Configuration options

Run `rivet --help` to see the full list of available flags. Some especially useful options are:

- **`--user-port`**
  - The port where your dev server is running (default: `3000`).
  - Rivet automatically detects common ports for frameworks like React, Vite, and Next.js, but you can override this if your setup uses a different port.
- **`--no-git-tracking`**
  - Git tracking defaults to enabled. Rivet creates a branch and commits successful changes automatically.
  - To manage git operations yourself, use `--no-git-tracking` to disable automatic git operations.

