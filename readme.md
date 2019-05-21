# Software Engineering A Practitioner's Approach

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

## Conducting Component-Level Design

- Step1. Indentity all design classes that correspond to the problem domain
- Step2. Undetify all design classes that correspond to the infrastructure domain
- Step3. Elaborate all design classes that are not acquired as resuable components
- Step3a. Specify message details when classes or components collaborate
- Step3b. Indentify appropriate interfaces for each component
- Step3c. Elaborate attributes and define data types and data structures required to implement them
- Step3d. Describe processing flow within each operation in detail
- Step4. Describe persistent data sources (databases and files) and identity the classes required to manage them
- Step5. Develop and elaborate behaviroal representations for a class or component
- Step6. Elaborate deployment diagrams to provide additional implementation detail
- Step7. Refactor every component-level design representation and always consider alternatives

## The Golden Rules of User Interface Design

- Place the User in Control
  - Define interaction modes in a way that does not force a user into unecessary or undesired actions
  - Provide for flexible interactions
  - Allow user interaction to be interruptible and undoable
  - Streamline interaction as skill levels advance and allow the interaction to be customized
  - Hide technical internals from the casual user
  - Design for direct interaction with objects that appear on the screen
- Reduce the User's Memory Load
  - Reduce demand on short-term memory
  - Establish meaningful defaults
  - Define shortcuts that intuitive
  - The visual layout of the interface should be based on a real-world metaphor
  - Disclose information in a progressive fashion
- Make the Interface Consisitent
  - Allow the user to put the current task into a meaningful context
  - Maintain consistency across a complete product line
  - If past interactive models have created user expections, do not make changes unless there is a compelling reason to do so

## Design Issues

- Response Time
- Help Facilities
- Error Handling
- Menu and Command Labeling
- Application Accessibility
- Internationlization

## Interface Design Principles

- Principles that lead to better usability
  - Anticipation
  - Communication
  - Consistency
  - Controlled Autonomy
  - Efficiency
  - Flexibility
  - Focus
  - Human Interface Objects
  - Latency Reduction
  - Learnability
  - Metaphors
  - Readability
  - Track State
  - Visible Navigation
- Dont's
  - Don't force the user to read voluminous amounts of text, particularly when the text explains the operation of the WebApp or assists in navigation
  - Don't make users scroll unless it is absolutely unavoidable
  - Don't rely on browser functions to assist in navigation
  - Don't allow aesthetics to supersede functionality
  - Dont' force the user to search the display to dertermine how to link to other content or services

## Interface Design Workflow for Web and Mobile Apps

- Review information contained in the requirements model and refine as required
- Develop a rough sketch of the WebApp interface layout
- Map user objectives into specific interface actions
- Define a set of user tasks that are associated with each action
- Storyboard screen images for each interface action
- Refine interface layout and toryboards using input from aesthetic design
- Indetify user interface objects that are required to implement the interface
- Develop a procedural representation of the user's interface with the interface
- Develop a behanvioral representation of the interface
- Describe the interface layout for each state
- Refine and review the interface design model

## Design Tasks

- Examine the requirements model and develop a problem hierarchy
- Determine if a reliable pattern language has been developed for the problem domain
- Beginning with a board problem, determine whether one or more architectural patterns are avaliable for it
- Using the collaborations provided for the architectural patterns, examine subsystem or component-level problems and search for appropriate patterns to address them
- Repeat steps 2 through 4 until all broad problems have been addressed
- If user interface design problems have been isolated (this is almost always the case), search the many user interface design pattern repositories for apporiate patterns
- Regardless of its level of abstraction, if a pattern language and/or patterns repository or individual pattern shows promise, compare the problem to be solved against the existing pattern(s) presented
- Be certain to refine the design as it is derived from patterns using design quality criteria as a guide

## Design Focus

- Information architecture patterns
- Navigation patterns
- Interaction patterns
- Presentation patterns
- Functional patterns

## WebApp Design Quality

- Usability
- Functionality
- Reliability
- Efficiency
- Maintainability
- Security
- Availability
- Scalability
- Time-to-Market

## Design Goals

- Simplicity
- Consistency
- Indentity
- Robustness
- Navigability
- Visual Appeal
- Compatibility
  
## Layout Guidelines

- Don't be afraid of open space
- Emphasize content
- Organize layout elements from top left to bottom right
- Group navigation, content, and function geographically within the page
- Don't extend your real estate with the scrolling bar
- Consider resolution and browser window size when designing layout

## Mobile-Apps Technical Considerations

- Multiple hardware and software platforms
- Many development frameworks and programming languages
- Many app stores with different rules and tools
- Very short development cycles
- UI limitations and complexities of iteraction with sensors and cameras
- Effective use of content
- Power management
- Security and privacy models and policies
- Computational and storage limitions
- Applications that depend on external services
- Testing complexity

## MobileApps Spiral Engineering Process

- Formulation
- Planning
- Analysis
- Engineering
- Implementation and Testing
- User Evaluation

## MobileApp Design - Best Practices

- Indentify your audience
- Design for context of use
- There is a fine line between simplicty and laziness
- Use the platform as an advantage
- Make scrollbars and selection highlighting more salient
- Increase discoverability of advanced functionality
- Use clear and consistent labels
- Clever icons should never be developed at the expense of users understanding
- Support user expections for personalization
- Long scrolling forms trump multiple screens on mobile devices

## Mobile Interactive Development Environments(MIDEs) Criteria

- General productivity features
- Third-party SDK integration
- Post-compilation tools
- Over-the-air deployment support
- End-to-end mobile application development
- Graphical user interface builders

