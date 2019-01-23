# Software Engineering

## The Process Framework

- Communication
- Planning
    - estimation
    - scheduling
    - risk analysis
- Modeling
    - analysis
    - design
- Construction
    - code
    - test
- Deployment
    - delivery
    - feedback

## Umbrella Activities

- Software project tracking and control
- Risk management
- Software quality assurance
- Technical reviews
- Measurement
- Software configuration management
- Reusability management
- Work product preparation an production

## The Essence of Practice

- Understand the problem
- Plan the solution
- Carry out the plan
- Examine the result

## General Principles

- The reason it all exists
- Keep it simple, stupid!
- Maintain the vision
- What you produce, other will consume
- Be open to the future
- Plan ahead for reuse
- Think!

## Personal Software Process

- Planning
- High-level design
- High-level design review
- Development
- Postmortem

## Agility Principles

- Our highest priority is to satisfy the customer through early and continuous delivery of valuable software.
- Welcome changing requirements, even late in development. Agile processes harness change for the customer's competitive advantage.
- Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale.
- Business people and developers must work together daily throughout the project.
- Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.
- The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.
- Working software is the primary measure of progress.
- Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.
- Continuous attention to technical excellence and good design enhances agility.
- Simplicity--the art of maximizing the amount of work not done--is essential.
- The best architectures, requirements, and designs emerge from self-organizing teams.
- At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.

## Industrial Extreme Programming 

- Readiness assessment
- Project community
- Project chartering
- Test-driven management
- Retrospectives
- Continuous learning

## Characteristics of a Software Engineer

- sense of individual responsibility
- acute awareness
- brutally honest
- resilience under pressure
- heightened sense of fairness
- attention to detail

## Principles That Guide Process

- Be agile
- Focus on quality at every step
- Be ready to adapt
- Build an effective team
- Establish mechanisms of communication and coordination
- Manage change
- Assess risk
- Create work products that provide value for others

## Principles That Guide Practice

- Divide and conquer
- Understand the use of abstraction
- Strive for consistency
- Focus on the transfer of information
- Build software that exhibits effective modularity
- Look for patterns
- When possible, represent the problem and its solution from a number of different 
- Remember that someone will mantain the software

## Communication Principles

- Listen
- Prepare before you communicate
- Someone should facilitate the activity
- Face-to-face communication is best
- Take notes and document desicions
- Strive for collaboration
- Stay focused; modularize your discussion
- If something is unclear, draw a picture
- Move on when
    - Once you agree to someone
    - If you can't agree to something
    - If a feature or function is unclear and cannot be clarified at the moment
- Negotitation is not a contest or a game. It works best when both parties win.

## Planning Principles

- Understand the scope of the project
- Involve stakeholders in the planning activity
- Recognize that planning is iterative
- Estimate based on what you know
- Consider risk as you define the plan
- Be realistic
- Adjust granularity as you define the plan
- Define how you intend to ensure quality
- Describe how you intend to accommodate change
- Track the plan frequently and make adjustments as required 

## Modeling Principles

- The primary goal of the software team is to build software, not create models
- Traval light--don't create more models than you need
- Strive to produce the simplest model that will describe the problem or the software
- Build models in a way that makes them amenable to change
- Be able to state an explicit purpose for each model that is created
- Adapt the models you develop to the system at hand
- Try to build useful models, but forgot about building perfect models
- Don't become dogmatic about the syntax of the model. If it communicates content successfully, representation is secondary
- If you instincts tell you a model isn't right even though it seems okay on paper, you peobably have reason to be concerned
- Get feedback as soon as you can

### Requirements Modeling Principles

- The information domain of a problem must be represented and understood
- The functions that the software performs must be defined
- The behavior of the software(as a consequence of external events)must be represented
- The models that depict information, function, and behavior must be partitioned in a manner that uncover detail in a payered(or hierarchical) fashion
- The analysis task should move from essential information toward implementation detail

### Design Modeling Principles

- Design should be traceable to the requirements model
- Always consider the architecture of the system to be built
- Design of data is as important as design of processing functions
- Interfaces(both internal and external)must be designed with care
- User interface design should be tuned to the needs of the end user. However, in every case, it should stress ease of use
- Component-level design should be functionally independent
- Components should be loosely coupled to one another and to the external environment
- Design representsations(models) should be easily understandable
- The design should be developed iteratively
- Creation of a design model does not preclude an alige approach

### Living Modeling Principles

- Stakeholder-centric models should target specific stakeholders and their tasks
- Models and code should be closely coupled
- Bidirectional information flow should be established between models and code
- A common system view should be created
- The imformation in the model must be presistent to allow tracking of system changes
- Information consistency across all levels of the model must be verfied
- Each model element has assigned stake holder rights and responsibilities
- The states of virous model elements should be represented

## Construction Principles

### Preparation Principles
Before you write one line of code, be sure you

- Understand the problem you are trying to solve
- Understand the basic design principles and concepts
- Pick a programming language that meets the needs of the software to be built and the environment in which it will operate
- Select a prigramming environment that provides tools that will make your work easier
- Create a set of unit tests that will be applied once the component you code is complete

### Coding Principles
As you begin writing code, be sure you

- Constrain your algorithms by following structured programming practive
- Consider the use of pair programming
- Select data structure that will meet the needs of the design
- Understand the software architecture and create interface that are consistent with it
- Keep conditional logic as simple as possible
- Create nested loops in a way that makes them easily testable
- Select meaningful variable names and follow other local coding standards
- Write code that is self-documenting
- Create a visual layout(e.g., indentation and blank lines)that aids understanding

### Validation Principles
After you have completed your first coding pass, be sure you

- Conduct a code walkthrough when appropriate
- Perform unit tests and correct errors you have uncovered
- Refactor the code

## Testing Principles

- All tests should be traceable to customer requirements
- Tets should be planned long before testing begins
- The Pareto principle applies to software testing
- Testing should begin "in the small" and progress toward testing "in the large"
- Apply to each module in the system a testing effort commensurate with its expected fault density
- Static testing techniques can yield high results
- Track defects and look for patterns in defects uncovered by testing
- Include test cases that demonstrate software is behaving correctly

## Deployment Principles

- Customer expectations for the software must be managed
- A complete delivery package should be assemabled and tested 
- A suppoer regime must be established before the software is delivered
- Appropriate instructional materials must be provided to end users
- Buggy software should be fixed first, delivered later

## Analysis Rules of Thumb

- The model should focus on requirements that are visible within the problem or business domain. The level of abstraction should be relatively high.
- Each element of the requirements model should add to an overall understanding of software requirements and provide insight into the information domain, function, and behavior of the system.
- Delay consideration of infrastructure and other nonfunctional models until design.
- Minimize coupling throughout the system.
- Be certain that the requirements model provides value to all stakeholders.
- Keep the model as simple as it can be.

## Class-Responsibility-Collaborator Modeling

- Classes
- Responsibilities
    - System intelligence should be distributed across classes to best address the need of the problem
    - Each responsibility should be stated as generally as possible
    - Information and the behavior related to it should reside within the same class
    - Information about one thing should be localized with a single class, not distributed across mutiple classes
    - Responsibilites should be shared among related classes, when appropriate
- Collaborations

## Requirements Modeling

- Content model
- Interaction model
- Functional model
- Navigation model
- Configuration model

## Quality Attributes FURPS

- Functionality
- Usability
- Reliability
- Performance
- Supportability

## Characteristics of well-formed design class 

- Complete and sufficient
- Primitiveness
- High cohesion
- Low coupling

## Taxonomy of Architectural Stytles

- Data-Centered Architectures
- Data-Flow Architectures
- Call and Return Architectures
- Object-Oriented Architectures
- Layered Architectures

## Architectural Considerations

- Economy
- Visibility
- Spacing
- Symmetry
- Emergence
