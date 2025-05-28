# Course Tutorials

## Package requirements
Before we can begin, you will need to install the following Python packages to use the notebooks:
- `qiskit`
- `matplotlib`
- `pylatexenc`
- `jupyter`

Recall that the command to install Python packages is `pip install <package_name>`.
Always use a virtual environment when possible!

## Notebooks
### `python_intro`
This noebook goes through some of the basics of Python:
- Variables
- `if` condition
- `while` loops

### `entanglement_generation`
This notebook implements the circuit needed to generate entanglement between 2 qubits.

### `grover_two_qubits`
This notebook implements Grover's algorithm using 2 qubits.

# Getting started
To make sure you can run these notebooks you need the following:
- Install [Python 3.11](https://www.python.org/downloads/release/python-3110/): This has been tested with 3.11 but feel free to try it out with your existing installations if you have Python on your system already.
- Clone the repository: `git clone https://github.com/QuLearnLabs/tutorials.git`.
- Make a virtual environment in the root folder of the repository: `python -m venv .venv`
- Activate the virtual environment: `source .venv/bin/activate`
- Install the packages rqeuired:
    - `qiskit`
    - `matplotlib`
    - `pylatexenc`
    - `jupyter`

# License
This project is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International [License](LICENSE.md).
The tutorials use among others Qiskit, an open-source SDK for quantum computing by IBM, licensed under Apache 2.0.