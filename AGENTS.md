# AGENTS Guide for bash-monokai-theme

## 🏗️ Architecture & Structure
This repository contains compiled theme files (e.g., `Monokai_Octagon`, `Monokai_monochrome`) used for the Bash shell, rather than a traditional application codebase. Development primarily involves creating and refining these themed asset packages.

*   **Core Artifacts**: The primary outputs are the directories found in the root:
    *   `Monokai_octagon/`: Contains the Octagon variation of the Monokai color scheme.
    *   `Monokai_monochrome/`: Contains a monochrome version of the Monokai color scheme.

## ⚙️ Development Workflow
Since this is an asset repository, standard build/test steps are not applicable or obvious. The workflow relies on theme generation scripts (which are assumed to be run externally or via non-standard means).

*   **Setup**: No explicit dependencies listed in manifest files were found. Themes should be placed directly into the appropriate directory structure for use.
*   **Testing/Validation**: There is no clear, defined testing suite (`npm test`, `pytest`, etc.) present in the codebase. Validation of a theme requires visual inspection and manual verification against design standards.

## 💡 High-Signal Facts / Gotchas
*   No complex build commands or standard dev server setup needs to be added here as none were found. Focus on documentation for how themes are generated and packaged externally.