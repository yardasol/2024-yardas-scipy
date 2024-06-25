In larger established software projects, developers can leverage a pre-existing
community as a resource to drive design, obtain feedback, and review code. Newer
or smaller projects typcially will not have a commuinity like this, and
developers of these projects must make design decisions on their own and without
feedback from users. With a small team, making well thought out design desicions
and comprehensive documentation takes time and energy away from implementation,
and in the fast paced world of academia, many developers make a choice to focus
on the end result of their research rather than the quality of their code. This
has the unfortunate side effect of making their software difficult to maintain
and not very extendible. Another way of putting this is these practices decrease
the sustainability of the code.

Sustainability can also refer to environmental, societal, personal, and
economic. In the context of this poster we refer to technical sustainability.

Guiding Questions
1. How can developers of smaller software projects maximize their
    sustainability? What practices can they do?
2. How can a new developer come in to a small project to take over the
   maintainer role? What does that look like?
3. 

What works:
    - ENGINEER your software (make a plan, THEN start developing)
        I used GitHub Discussions to do this so there is a record of the design
        discussion. This is not be the most structured way to make design
        decisions. A better approach would be to using an AKM (architectural
        knowledge management) model or tool. ADDM seems to be a good and comprehensive one
        (cite carillo 2015, guidelines and ...). However in the current year,
        these tools have proved diffcult to easily find. I do believe that using
        this kind of tool IS doabe for small developers, and it a way one can
        sustain knowledge about their project in an organized and accessible
        way.
    - Small, targeted commit messages help you stay organized. This is commonly
        accpeted good practices.
    - Write comprehensive documentation. This is the step where many developers
        get lazy, as documentation like this is typically the last thing to be
        written. Instead of waiting til the end of the project/thesis/paper to
        write docuentation, write examples/guides along side the code along with
        the normal presence of docstrings. It's even better if you webhost
        documentation using github pages or another free service.
    - For a more comprehensive overivew, check out "Best practices" or "good
        enough practices" papers

Strategies to increase code sustainability and build community:
    - A big part of sustainability of a software project is the presence of a
      community. People in the community will use the software, suggeste
      features, report and fix bugs, and generally improve the project.
    - A good way to build community is 1) make your project as user-friendly as
      possible (web hosted docs with guides and examples, explanation of input
      and output files), 2) Provide a place for your community to engage (I used
      github discissions for this), and 3) a little bit of luck!
    - Using input schemas gives input files not only a defined structure, but a
        way to check their correctness before execution. This gives code a more
        professional feeling, and any changes in the input file structure will
        be reflected in the change of the schema.
    - Using automation as much as possible will make your job easier in the long
        run. At the very minium, having an automated testing workflow set up
        will enable you and your growing community to detect bugs from
        contributions to code before they are merged.
    - Follow well established practices for coding: use smart variable names. If
        you are simulating a physical system, name the variables accordingly.
        Have someone else look at your code before merging any changes, even if
        you think a change is trivial. 

Dependency snags:
( do I even want to discuss this? )
    - Sometimes in a software project, you will run into issues with
        dependencies. This must be addressed and can be very frustrating to deal
        with. 

Main takeaway:
    - 
