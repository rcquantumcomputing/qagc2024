# qagc2024

Early code for the QunaSys QAGC hackathon: https://www.qagc.org
## Setup

Tested with Python 3.10.11

Follow these steps to set up the project:

1. **Set up the virtual environment and install dependencies**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```

2. **Run the project**
   ```bash
   jupyter notebook app/src/bencmark_vqe_upd.ipynb
   ```
#
##### Several parts of this project were inspired from the Official Qiskit Repository and IBM Quantum Tutorials, including but not limited to:
* https://qiskit-community.github.io/qiskit-algorithms/stubs/qiskit_algorithms.AdaptVQE.html <br>
* https://docs.quantum.ibm.com/api/qiskit/0.40/qiskit.algorithms.optimizers.QNSPSA <br>
* https://docs.quantum.ibm.com/api/qiskit/0.40/qiskit.algorithms.minimum_eigensolvers.AdaptVQE <br>
* https://learning.quantum.ibm.com/tutorial/variational-quantum-eigensolver
* https://github.com/Qiskit
* https://github.com/mayhallgroup/adapt-vqe
##### Some papers we were inspired from for our project are the following:
* https://www.nature.com/articles/s41467-019-10988-2
* https://arxiv.org/abs/1909.02108
* https://arxiv.org/abs/2112.14077
