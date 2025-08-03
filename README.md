# Course Tutorials

##  Getting started
To make sure you can run these notebooks you need the following:
- Install [Python 3.12.9](https://www.python.org/downloads/release/python-3129/): This has been tested with 3.12.9 but feel free to try it out with your existing installations if you have Python on your system already.
- Clone the repository: `git clone https://github.com/QuLearnLabs/tutorials.git`.
- Make a virtual environment in the root folder of the repository: `python -m venv .venv`
- Activate the virtual environment: `source .venv/bin/activate`
- Install the required packages using `pip install -r requirements.txt`

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

# License
This project is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International [License](LICENSE.md).
The tutorials use among others Qiskit, an open-source SDK for quantum computing by IBM, licensed under Apache 2.0.