# QuantumRNG
Using a simulated quantum circuit (with IBM's Qiskit) to generate random numbers from a provided range

Obviously not intended to be practically useful, rather an example for practicing basic operations in Qiskit:

* Circuit creation
* Circuit visualization
* Statevector visualization

Uses the Fast Dice Roller algorithm



Note: the implementation using a simulator is not cryptographically secure as [qiskit uses the Mersenne Twister](https://docs.quantum.ibm.com/api/qiskit/release-notes/0.20) under the hood. I left notes about changing the backend in the notebook - by connecting to IBM Cloud with your token and running the circuit on [an actual quantum computer](https://quantum.ibm.com/services/resources?tab=systems) one would get a truly random source of entropy, hence the idea of this project.
