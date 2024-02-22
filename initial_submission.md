SaltProc: An open-source wrapper for simulating batchwise reprocessing in nuclear reactors.
-------------------------------------------------------------------------------------------

Abstract
~~~~~~~~
SaltProc is an open source tool for simulating batch-wise reprocessing of fuel
in nuclear reactors. Originally developed as a wrapper around a closed source
depletion solver, the introduction of depletion capabilities to OpenMC, a
community-developed neutron transport code, inspired me to implement support
for OpenMC to have the option for a fully open software stack. My poster will
focus on the development process of adding this feature as well as discuss
design decisions that were made, and show results comparing the two depletion
solvers in the final implementation.

Description
~~~~~~~~~~~
Neutron radiation in the fuel inside of a nuclear reactor induces nuclear
fission in certain nuclides like U235. The fission reaction causes the
nucleus to break apart, releasing both energy and new nuclides, many of which
are radioactive isostopes of smaller elements. This process
is referred to as depletion or burnup. Some of these nuclides inhibit the
nuclear reaction, and greater fuel efficency can be achieved by chemical
reprocessing of the fuel to remove them.

SaltProc was originally developed to wrap around Serpent2, a closed source
neutron transport code with a depletion solver. While the original developer
of SaltProc had intended for it to be code-agnostic, this design
pattern can be challenging to implement effectively when not also explicitly
to bring this design patter into SaltProc.

In this poster, I will cover:
- My approach to bringing effective code-agnosticism into a previously existing project
- The difficulties of taking on the role of maintainer in a code that I did not author
- Utility of technologies like schemas in making code-agnostic input validation
- The results of my code additons compared to the old imlementation.

I had to perform major refactoring of many parts of the code to
make it more code-agnostic. Particularly of note,
I extracted the generic methods and attributes from the current code
interfacing class into an abstract base class to act as a template for code-specifc
interface classes. I also overhauled the input file system to match this design
philosphy and added input validation via schemas.
