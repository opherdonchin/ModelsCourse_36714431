# Models of the Motor Systems (Course 36714431) - Semester 2026-2

Welcome to the public course materials repository for Models of the Motor Systems.

This repository includes:

- Syllabus
- Lecture slides
- Lecture notebooks
- In-class notebooks
- Homework materials

## Fastest Option: Run in Colab

Every notebook includes an Open in Colab button near the top.

If you want the quickest start:

1. Open a notebook on GitHub.
2. Click Open in Colab.
3. Run cells directly in Colab.

## Local Setup (Beginner-Friendly, VS Code Only)

These steps assume you are new to local Python work.

### 1. Install VS Code

1. Download from https://code.visualstudio.com/
2. Install and open VS Code.

### 2. Install VS Code Extensions

In VS Code, install these extensions:

- Python (Microsoft): ms-python.python
- Pylance (Microsoft): ms-python.vscode-pylance
- Jupyter (Microsoft): ms-toolsai.jupyter
- Python Environments (Microsoft): ms-python.vscode-python-envs
- Pixi VSCode: jjjermiah.pixi-vscode

These are high-value and low-overhead for this course workflow.

### 3. Install pixi

pixi manages the full project environment, including Python and package versions.

1. Install pixi from https://pixi.sh/latest/
2. Close and reopen VS Code after installation.

### 4. Install GitHub Desktop

1. Go to https://desktop.github.com/
2. Download and install GitHub Desktop.
3. Sign in with your GitHub account.

### 5. Clone This Repository with GitHub Desktop

Quick option from GitHub website:

1. Open the repository page on GitHub.
2. Click the green Code button.
3. Choose Open with GitHub Desktop.
4. Confirm the local folder and clone.

Manual option in GitHub Desktop:

1. In GitHub Desktop, choose File > Clone repository.
2. Select URL.
3. Paste this repository URL:
   https://github.com/opherdonchin/ModelsCourse_36714431.git
4. Choose a local folder and click Clone.
5. In GitHub Desktop, use Repository > Open in Visual Studio Code.

### 6. Create the Local Environment

Open a terminal in VS Code at the repository root and run:

pixi install

This reads pixi.toml and sets up the complete environment.

### 7. Run Notebooks Locally (VS Code)

1. Open an ipynb file in VS Code.
2. Select the pixi-managed Python kernel when prompted.
3. Run cells in order from top to bottom.

## Troubleshooting Quick Tips

- If pixi command is not found, restart VS Code and open a new terminal.
- If the notebook kernel is missing, run pixi install again and reselect kernel.
- If you only need to run quickly, use Open in Colab instead of local setup.
