# AGENTS.md

## Cursor Cloud specific instructions

This repository (**Kaysar**) is currently an empty skeleton project. It contains only a README, LICENSE (AGPL-3.0), and a `.gitignore` referencing `appengine-generated/`, which hints at future Google App Engine usage.

### Current state

- **No source code, dependencies, build systems, or services** exist yet.
- **No lint, test, or build commands** are available.
- The `.gitignore` entry for `appengine-generated/` is the only signal about potential future tech stack choices.

### For future agents

- Once application code is added, update this file with service startup instructions, dev commands, and any non-obvious caveats.
- No update script dependencies are needed at this time; the `SetupVmEnvironment` script is a no-op (`echo "No dependencies to install"`).
