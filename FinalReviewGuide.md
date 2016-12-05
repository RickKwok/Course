* Implement software engineering practices in a team project.
* Identify practices related to software process.
* Decide how to test a system and measure coverage.
* Compare and contrast design techniques and architectural patterns.
* Measure the quality of software code.
* Build tools for supporting software engineering tasks.
* Evaluate evidence related to a software practice.
* Identify configuration management practices for improving maintanance of software
* Apply deployment practices and patterns.

### Agile

* Describe why agile software development was created
  (Agile provides opportunities to assess the direction of a project throughout the development lifecycle. In waterfall, development teams only have one chance to get each aspect of a project right. In an agile paradigm, every aspect of development — requirements, design, etc.)
* Explain why each of the core practices of Extreme Programming (XP) are effective(Sit together,Energized work,Weekly cycle,Slack,Test-first programming,Incremental design)
* Explain why each of the corollary practices of XP may be effective(Real customer involvement,Incremental deployment,Team continuity,Shrinking teams,Shared code.For example, daily deployment is useless if your team ships code filled with errors.)
* Analyze which XP practices are applicable you should use in your team
* Explain how to apply scrum and iteration planning to a project.(Teams planning by selecting stories from product backlog and commiting a set of them for execution in the upcoming iteration.)

### Design/Patterns/APIs

* Design notation(Dynamic:Data flow diagrams (DFDs).State transition diagrams (STDs).Statecharts.Structure diagrams.Static:
 Entity Relationship Diagrams (ERDs).Class diagrams.Structure charts.Object diagrams.)
* Understand use cases, wireframes, storyboards(A wireframe is a view schematic that captures all layout and content decisions of that view.A storyboard illustrates the timeline of user performing a task as a sequence of frames.A use case is a list of actions or event steps, typically defining the interactions between a role and a system, to achieve a goal.)
* Understand core concepts related Design Patterns
* Identify an architecture when you see it
* Pick an appropriate architecture for a problem
* Compare and contrast architectural choices
* Understand MVVM and databinding
* How to design an API
* Understand REST verbs(post--create;get--list;put/patch--update;delete-delete)
* Explain REST principles(Uniform Interface,Stateless Interactions,Cacheable,Client-Server,Layered System,Code on Demand)
* Explain difference between a framework and API(API is sum of all exposed functions/methods in a library that you can call. A framework is a big library that provides many services instead of specific ones, like most libraries do.)
* Use and explain above concepts in designing a product.

### Testing

* List and define different types of testing (e.g. acceptance testing:a system is tested for acceptability to see whether is deliverable or not vs integration testing: individual software modules are combined and tested as a group.)
* Compare and contrast black-box testing and white-box testing
* Generating test cases based on black-box testing.
* Generating test cases based on white-box testing.
* Define test harness(a collection of software and test data configured to test a program unit by running it under varying conditions and monitoring its behavior and outputs. It has two main parts: the test execution engine and the test script repository.), tear-down(the act of disassembling a product to identify its component parts and functions), setup, test cases, test suite(collection of test cases), assertions(An assertion is a boolean expression at a specific point in a program which will be true unless there is a bug in the program.)
* Explain Test-driven testing (TDD:requirements are turned into very specific test cases, then the software is improved to pass the new tests)
* Implement unit tests and necessary assertions for testing a system.
Design a detailed testing strategy for a product, with appropriate arguments for types of testing used, explanations of trade-offs, and concrete implementation plans.
* Define mocking.
* Explain mocking versus other approaches (e.g. dependency injection)
* Explain advantages and disadvantages of mocking.(Mocking is used for protocol testing - it tests how you'll use an API, and how you'll react when the API reacts accordingly.On a practical note, mocking frameworks tend to have limitations around mocking classes)
* Implement mocking of RESTful services, database, or file system interfaces.
* Explain web testing with selenium
* Implement xpath expressions for asserting web page behavior

### Metrics/Static Analysis

* Understand metrics, including complexity, OO, and other techniques.
* Understand and derive program graph from code snippet.
* Define line, branch, condition, branch-condition and MCDC coverage.
* Explain subsumption and why and when one type of coverage may subsume another.
* Calculate line, branch, condition coverage.
* Identify other kinds of coverage: path coverage, mutation testing, data-flow coverage.
* Explain benefits and disadvantages of using Visitor pattern in static analysis(the arguments and the return type of visiting methods have to be known).
* Identify several uses cases for static analysis.
* Explain issues and benefits related to static analysis (e.g. versus dynamic analysis or verification.).
* Implement static analysis for measuring errors or code quality measures.

### Empirical/Interviews

* Explain how to collect evidence about a software engineering practice.
* Explain issues related to interviews
* Identity possible interviews and strategies to improve interviews

### Configuration Management/Continuous Deployment/Infrastructure

* Understand core concepts related to Configuration Management(a set of tracking and control activities that are initiated when a software engineering projects begins and terminates when software is taken out of operation)
* Identity traditional and modern components and practices related to configuration management(traditional:1.Identify all items related to software.2.Manage changes to those items.3.Enable variations of items and changes.4.Maintain quality of versions and releases.5.Provide traceability between changes and requirements.In modern configuration management, lightweight CM is integrated throughout the software process)
* Explain issues related to (not using configuration management) 
* Design and apply configuration management concepts to a project.
* Explain differences between continuous integration, deployment, and delivery(Continuous Deployment is the deployment or release of code to Production as soon as it is ready.Continuous Delivery is the continual delivery of code to an environment once the developer feels the code is ready to ship.Continuous Integration is the practice of merging development work with a Master/Trunk/Mainline branch constantly so that you can test changes, and test that changes work with other changes.)
* Explain operations responsibility models and team values
* Identity Deployment Strategies
* 10 Adages Paper
* Identity components of cloud infrastructure(Cloud infrastructure refers to the hardware and software components -- such as servers, storage, networking and virtualization software -- that are needed to support the computing requirements of a cloud computing model. In addition, cloud infrastructures include a software abstraction layer that virtualizes resources and logically presents them to users through programmatic means.)
* Explain underlying issues related to infrastructure components
* Understand microservices
* Design and apply infrastructure concepts for the design of a scalable and resilence application.
* Explain concepts related to docker, vagrant, and ansible

### Productivity

* Describe common issues and strategies related to productivity
* Describe impact related to context switching
* List the problems that PSP solves.
* List the items that can be tracked (traditionally and modern sense).
* Explain how progress can monitored and measured.
* Explain benefits and issues related to using PSP.
* Design a PSP system to track your progress as a developer.
* List some examples of social software processes.
* Explain benefits related to social software processes.
* Explain issues that may arise with use of social software processes.
* Design a Social Software Process that can be used by a software company or community.
