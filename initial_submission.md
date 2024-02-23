# Lessons from working on SaltProc: An open-source wrapper for simulating batchwise reprocessing in nuclear reactors.

## Abstract
SaltProc is an open source tool for simulating batch-wise reprocessing of fuel
in nuclear reactors. Originally developed as a wrapper around a closed source
depletion solver, the introduction of depletion capabilities to OpenMC, a
community-developed neutron transport code, inspired me to implement in interface to it
for a fully open software stack. My poster will focus on the development process of
adding this feature as well as discuss design decisions that were made, problems I ran
into during the development process, improvements to the sustainability of the software.
Finally I will show results comparing the two depletion solvers in the final implementation.

## Description
Neutron radiation in the fuel inside of a nuclear reactor induces nuclear
fission in certain nuclides like U235. The fission reaction causes the
nucleus to break apart, releasing both energy and new nuclides, many of which
are radioactive isostopes of smaller elements. This process
is referred to as depletion or burnup. Some of these nuclides inhibit the
nuclear reaction, and greater fuel efficency can be achieved by chemical
reprocessing of the fuel to remove them.

SaltProc is a code for simulating chemical fuel reprocessing for nuclear reactors.
It was originally developed to wrap around Serpent2, a closed source
neutron transport code with a depletion solver. While the original developer
of SaltProc had intended for it to be code-agnostic, my experience with the code
tells that this design pattern can be challenging to implement effectively in advacne
when leaving the interface implementation for other codes to future developers.

In this poster, I will cover:
- The basic mathematics of depletion. (maybe remove this one)
- My approach to bringing effective code-agnosticism into a previously existing project
- The difficulties of taking on the role of maintainer in an open-source code with a small userbase
- Various snags I ran into related to dependencies and how I solved them
- Utility of technologies like input schemas and CI for code sustainability
- How I improved the sustainability of the code by improving documentation, variable names, and program flow.
- The results of my code additions compared to the old imlementation.

My indented audience is folks who are starting to get into open source software
development, as well as developers who are interested in software sustainability,
who want to learn more about...

## Notes
This could also be in the Maintainers and community track.
Link to docpages

Notes from writing session:
- try to focus on things that not everyone might be an expert in.
- Maybe say who your audience is
- Address who the audience for your talk is and what they are going to learn in the talk
- Tell story about how I made the project sustainable (adding documentation, updating variable names and documentation)
- In sustainable, we mean the torch can be passed (e.g. documentation, CI, examples)
- What could have made the process from going from a user to a developer more smooth? Maybe try to frame it this way
- S
