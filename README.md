# Quantum Matchup Generator
## Description
With the power of random number generation in quantum computing, we can use it to create a tournament matchup generator
## Setting up
Download and upload the jupyter notebook into IBM Quantum Experience
## How to use
1. Run the first block of the notebook to load up the libraries and the following inputs:
  * The amount of players that are going to needed to be generated (e.g 1v1 {2} or 1v1v1{3}, etc...)
  * Enter the name into the list of players that are participating in the matchup. Once you are done with all the names inserted, press enter and it will finialize the list
2. Run the third block, which contains the function need to perform the action of RNG for block 2.
3. Run the second block as many times as you want, if you need to add names to the list or remove, refer back to number 2
## Libraries
 ``` qiskit ```<br>
 ``` qiskit.tools.jupyter ```<br>
 ``` ibm_quantum_widgets ```
<br>(These Libraries don't need to be installed if you are using the notebook in IBM Quantum Experience)
