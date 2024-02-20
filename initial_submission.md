SaltProc: An open-source wrapper for simulating batchwise reprocessing in nuclear reactors.
-------------------------------------------------------------------------------------------

Abstract
~~~~~~~~
SaltProc is an open source tool for simulating batch-wise reprocessing of fuel in nuclear reactors. Originally developed as a wrapper around a
closed source depletion solver, the introduction of depletion capabilities to
OpenMC, a community-developed neutron transport code, inspired me to implement
support for OpenMC to have the option for a fully open software stack.
My poster will focus on the development process of adding this feature as well as discuss design decisions that were made, and show results comparing the two depletion solvers in the final implementation.

Description
~~~~~~~~~~~
This project required extensive refactoring to update docstrings and variable
names, as well as changed some of the code strucute and added new features,
like input validation using a JSON schema. 

(mention how i restructured the code to have a generalizable interface to other depletion codes)

