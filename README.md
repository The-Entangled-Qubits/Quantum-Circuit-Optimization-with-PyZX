# Quantum_Computing_with_Qiskit

This is the Entire walkthrough of what I am following right from installation of Qiskit to some sample codes to implement. The repository reflects my understandings and work on Qiskit. Lets Start ✨

## Introduction

Qiskit is an open source SDK for working with quantum computers at the level of pulses, circuits and algorithms. Main goal of Qiskit is to build a software stack that makes it easy for anyone to use quantum computers. Qiskit can be used to easily design experiments and run them on simulators and real quantum computers.
Qiskit consists of four foundational elements:

- [Qiskit Terra](https://qiskit.org/documentation/the_elements.html#terra): Composing quantum programs at the level of circuits and pulses with the code foundation.

- [Qiskit Aer](https://qiskit.org/documentation/the_elements.html#aer): Accelerating development via simulators and noise models

- [Qiskit Ignis](https://qiskit.org/documentation/the_elements.html#ignis): Addressing noise and errors

- [Qiskit Aqua](https://qiskit.org/documentation/the_elements.html#aqua): Building algorithms and applications

# Installations 

I would be doing it on mainly on Google Colab and on my Ubuntu system too. It is recommended to use Python virtual environments to cleanly separate Qiskit from other applications for better experience. This issue is resolved for Google colab and as I am running Ubuntu on my VirtualBox, I would be directly installing the package there.

## Step 1 

This is the only step for successful installation of qiskit in Ubuntu and Google Colab too.
- For Ubuntu
```
pip install qiskit
```
- For Colab
```
!pip install qiskit
```
Cross check whether Qiskit is installed correctly or not
Run ``` qiskit.__qiskit_version__ ``` on Colab, the results should be look similiar as
```
{'qiskit': None,
 'qiskit-aer': '0.6.1',
 'qiskit-aqua': '0.7.5',
 'qiskit-ibmq-provider': '0.10.0',
 'qiskit-ignis': '0.4.0',
 'qiskit-terra': '0.15.2'}
 ```
 Now we are good to go 👍
