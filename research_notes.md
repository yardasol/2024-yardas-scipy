Venters et al. (2018):
    - Closest thing I could find to a review paper of software sustainabiliy in
        2018
    - Overview of software sustainability approaches and trends
    - Software systems are highly complex and require evolution and maintenance
        over time to satisfy needs of stakeholders
    - Internet has allowed "post-deployment" approach to software engineering:
        apps can be updated automatically, development versions can be released
        to users (see Fitzgerald 2017 for more on this)
    - This fast and loose approach makes software systems more fragile and
        prone to unexpected failure
    - Software sustainability very generally is the idea that systems should be
        maintainabile and extendable (Amri and Saoud 2014)
    - "Software architectures are the foundation of any software system, as
        they provide 'the fundamental organistaion of a system embodied in its
        components, their relationships to each other, and to the environment,
        and the principles guiding its design and evolution'(ISO 2007)"
    - Section 2: Outline different dimensions of software sustainability
        - Various different definitions/viewpoints of software sustainability
            - sustainable software (technical sustainabiity) VS
                software engineering 4 sustainabiliy (sustainability issues
                outside of the software itself) (see Penzenstadler 2013)
            - Karlskrona Manifesto (Becker et al 2014): argues sustainability is
                a construct across five dimensions
                    1. Economic: focuses on assets, capital, value that comprise
                       weath creation, income, etc
                    2. Environmental: effects of human activities on nature,
                       climate
                    3. Individual: well being of people, education, mobility
                    4. Social: groups, factors that erode trust in society,
                       justice
                    5. Technical: Longevity of information, infrastrucutre, and
                       their evolution in a changing world
                There exists interdependencies between these dimensions
            - Hilty and Aebischer, 2015: impact on sustainability in each of the
                five dimensions manifests in three orders of effect:
                1. First order: systems are built and used for their intended
                   purpose
                2. Second order: System induces new types of behavior over time
                3. Third order: compounded effects from large scale, long term
                   use of the system
        - Sustainability is not widley understood/agreed upon in field of
            software engineering. Proposed formal definitions generally focus on
            software system's capacity to enduere (endure what exactly?)
        - Focus of sustainability research in software engineering has focused
            on models to develop sustainable software, approaches for evaluating
            sustainability
            - *Maybe loop back to these later, could be useful for analysis*
        - There are also models for softawre sustainability evaluation.
        - Three main concepts this article focuses on
            1. Software sustainability: capacity of software to "endure"
            2. Software *architecture* sustainability: capacity of software to
               endure is contingent upon its structures and their ability oto
               evolve
            3. Sustainabile architecture design decisions: the architecture
               reflects the design decisions.
        - 
    - section 3: Address sustainability from an architectuer POV
        - Software architectures are the critical factor in the capacity of
            software systems to endure and evolve
        - Sustainability of architecture requires the ability to tolerate
            changes (from shifts  in requirements, technologies, goals, etc)
        - Artchitecutre sustainability is *degraded* by two phenomena:
            1. architecture drift: divergence from underlying architecture
            2. architecture erosion: when source code becomes sub-optimal
               compared to the designed architecture\
        - One approach to design flexible open archtictures that are
            sustainable: design them to accomodate future changes to a greater
            extent withoout significant change to the basic structure of the
            system with minimal cost (omfg this sentence is gonna be the end of
            me)
        - reference archituectures embody the architectural knowledge of
            success. However many seferecne archicteuctures have not survived
        - Principal factors that make referencece architectures sustaina
        - *Critical factor in long-term existsnce of reference architectures is
            that their communities sustain them.*
    - Section 4: Describe how architecture design decisions must be sustainable
        - Sustainability debt: how technical debt can be used to identify the
            effects of software design decisions on sustainability
        - Sustainability of software design relys on factors required to capture
            design decisions, in particular lack of tools to captures
            architectural knowledge (AK)
    - Section 5: Address software metrics related to estimating sustainability
        - Code 
    - Section 6: Provides perspectives from academia, awareness of
      sustainability w.r.t scientific and engineering research software
        -  
    - Section 7: Open isses

Venters et al. (2023):
    - all software intensive systems have an architecture even when it is not
        explicitly designed. These accidental software architectures are
        underpinned by sub-optimal design decisions that exacerbate
        complexity -> foundation for software decaty and death in investment.
    - Research software should be a sustainable, fisrt class, experimental
        scienteific instrument.
    - Architecturally significant requirements: extensibility, maintainability.
