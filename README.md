# Vlasov Solver

## Getting Started

1. Install [Hatch](https://hatch.pypa.io/latest/). The installation guide for Hatch can be found [here](https://hatch.pypa.io/latest/install/#installation).
   
    Hatch is a Python project manager. It mainly allows you to define the virtual environments you need in [`pyproject.toml`](https://github.com/PlasmaControl/pancakecoilopt/blob/main/pyproject.toml). Then, it takes care of the rest. Also, you don't need to install Python. Hatch will install it when you follow the steps below.

2. Clone the repository.
    ```
    git clone https://github.com/sinaatalay/VlasovSolver.git
    ```
3. Go to the `VlasovSolver` directory.
    ```
    cd VlasovSolver
    ```
4. Start using one of the virtual environments by activating it in the terminal.

    Default development environment with Python 3.13:
    ```bash
    hatch shell default
    ```
5. Finally, activate the virtual environment in your integrated development environment (IDE). In Visual Studio Code:

    - Press `Ctrl+Shift+P`.
    - Type `Python: Select Interpreter`.
    - Select the virtual environment created by Hatch.


All the source code should be written in the `vlasovsolver` directory. `run.ipynb` should be used as an example of how to use the code.

## Suggested development environment

1. Install VS Code.
2. Install extensions:
   1. Even Better TOML (for `pyproject.toml`)
   2. Ruff (for linting)
   3. Python (for Python support)
   4. Jupyter (for `run.ipynb`)
   5. Typst (for report)
