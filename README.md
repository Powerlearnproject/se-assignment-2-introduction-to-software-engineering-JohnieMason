[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15284910&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
What is software engineering, and how does it differ from traditional programming?
The application of engineering principles to design, develop, test, and maintain software systems is what software engineering entails. It involves a systematic, disciplined, and quantifiable approach to creating and managing software. This ensures that the resulting products are reliable, efficient, and fulfill user requirements.
Depending on scope and complexity: Software Engineering is broad as it involves designing, developing, maintaining and managing large-scale systems while traditional programming is narrow as it focuses on the writing code for specific tasks or small applications
Methodologies: Software programming has a structured methologies like SDLC, Agile, waterfall etc while traditional programming is less formal as it is matter of ad-hoc.
Quality Assurance and Testing: Software programming incorporates rigorous testing stategiesi.e unit, integration, system and acceptance testing while traditional programning involves the basic functional testing by the programmer.


Software Development Life Cycle (SDLC):
Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Requirements Analysis: Detailed user requirements are acquired and recorded in this stage. To make sure that all functional and non-functional needs are recognized and comprehended, analysts collaborate closely with stakeholders.
Design: The requirements are converted into a comprehensive system architecture and design specifications during the design process. In order to ensure a strong basis for implementation, this involves designing the system's components, interfaces, data flow, and user interfaces.
Implementation (Coding): Using the design guidelines as a guide, developers write and put together the actual code during this step. Best practices and coding standards are adhered to in order to guarantee quality and maintainability.
Testing: Defects are found and fixed through testing. In order to make sure the software satisfies all criteria and is free of serious problems, this phase involves unit testing, integration testing, system testing, and user acceptance testing.
Deployment: The production environment is where the software is installed and configured. To guarantee a seamless transition, this phase may also entail data migration, user training, and final validation.
Maintenance: Following deployment, the program goes through a phase of continuous support, bug repairs, upgrades, and additions to adjust to evolving user requirements and surroundings.

Agile vs. Waterfall Models:
Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Procedure for Development:
Agile: Adopts a gradual, iterative methodology that permits ongoing input and enhancements throughout the project's development.
Waterfall: Employs a sequential, linear process in which modifications are challenging to execute after a phase is finished. Each phase must be finished before the next can start.
Adaptability
Agile: Extremely adaptable, encouraging adaptive planning and evolutionary development while tolerating modifications and new requirements even in the last stages of the development process.
Waterfall: Rigid, having a predetermined scope that is established at the outset; modifications are expensive and difficult to incorporate once the project has commenced.
Client Participation:
Agile: Ensures the end product fulfills the needs of the client while building a solid working relationship by involving them in the development process on a frequent basis and soliciting input.
Waterfall: User expectations may not be met since customer involvement is mostly at the requirements stage and there is little contact during development.
Planning and Documentation:
Agile: Prioritizes usable software over extensive documentation, with minimum but adequate documentation that highlights flexibility and direct communication.
Waterfall: May result in longer initial planning stages but ensures detailed specifications and designs through meticulous documentation and upfront preparation.

Requirements Engineering:
What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Requirements Engineering is a critical phase in the software DevelopmentCycle Life (SDLC) which incorporates systematic process of eliciting , analyzing, documenting, validating and ,managing the requirements of a software system.
Below is the process of Requirements Engineering:
Requirements Elicitation- this is a collection exercise of reuirements from stakeholders through different techniques like interviews, surveys, workshops, observations etc.
Requirements Analysis- This is evaluation and prioritization of the collected requirements to ensure they are clear, feasible, consistent and aligned with the project goals.
Requirements specification- This forms the basis of the SRS (Software Requirements Specification) document used by the developers, testers and other stakeholders as the reference.
Requirements Validation- This involves reviewing the documented requirements to ensure accuracy, completeness and agreement. Techniques lie reviews, inspections and prototyping are used.
Requirements Management-Tracking and managing changes to the requirements throughout the project liefecycle.
IMPORTANCE:
It forms the foundation for development since it guides design, implementation and testing.
Enables identification of issues, reducing costs (Risk Reduction)
Controls project scope and manages chnages.
Quality Assurance. provides basis for validation and verifcatio activities.

Software Design Principles:
Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
In software design, modularity refers to the division of a large, complex system into smaller, independent modules that have particular functions. Every module functions autonomously and exchanges information with other modules via clearly defined interfaces. Because updates or patches to one module may be applied without affecting others, this method reduces the possibility of unforeseen consequences throughout the system and enhances maintainability. Because developers can concentrate on understanding and maintaining fewer, more cohesive blocks of code, it also improves readability and understandability. Furthermore, modularity encourages code reuse by allowing well-tested modules to be used in numerous system components or in upcoming projects, accelerating development and guaranteeing consistency.
Modularity contributes to scalability because it makes system growth and adaptability easier. Rather of rebuilding the entire system, new modules can be added or existing ones can be modified to introduce new features or advancements. The ability to work independently on different modules thanks to this modular flexibility speeds up overall development durations and facilitates parallel development activities. Additionally, modular systems provide deployment flexibility by enabling the deployment of modules singly or in combinations to accommodate various deployment requirements or situations. Modular design is essential for creating flexible, adaptive software systems that can change with the needs of businesses and technology environments due to its scalability and flexibility.

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
Unit Testing-Software modules or components should be tested separately. It confirms that every unit operates in accordance with its design and specifications.
Intergration Testing- To make sure things function as intended, test how integrated units or modules interact with one another. It validates the component interfaces and interactions.
System Testing- Testing every integrated module and component of the system as a whole. It verifies the system in comparison to the given functional specifications and requirements.
Acceptance Testing- Customers, stakeholders, or end users test the software to see if it satisfies their acceptance requirements. It could involve both internal alpha testing and external beta testing.
IMPORTANCE:
Defect Detection-defects are detected and resolved in early stages of SDLC
Quality Assurance- Ensures the software meets the quality standards.
Risk Mitigation- Reduces chance of software failure.
Customer Satisfaction- Validates the software meets the user expectations.

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Version control systems, or VCSs, log alterations to source code and make it easier for engineers to work together. They guarantee the integrity of the code, allow for version rollbacks, and facilitate conflict-free concurrent operations.
Examples are: Git- Distributed VCS known to be fast, data intergrity and support for merging and branching workflows
Subversions(SVN)-Centralized VCS with a client server architecture, featuring versioning of directories and files.
Mercurial- Distributed VCS overing scalability, efficiency and an intuitive coomand set for managing projects.

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Roles of a project manager are:
Planning and scheduling
leading and motivating cross-functional teams ensuring clear communication and collaboration
Does risk management
Monitors the project progress, ensuring adherence to quality standards and customer requirements.

CHALLENGES: 
Changing requirements
tight deadlines
Technical debt

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Software maintenance is the process modifying and updating software after its initial releae to correct defects, improve performance or adapt to changes in the operating environmnent.
Types of Software Maintenance:
Corrective Maintenance-addressing and resolving problems or flaws found during testing or following deployment
Adaptive Maintenance- adjusting the software to take into account modifications to the hardware, software, or regulations.
Perfective Maintenance-enhancing the program through code optimization, speed enhancements, or new feature additions.
Preventive Maintenance- proactively recognizing and resolving such concerns to avoid complications later on

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Software developers may have to deal with moral dilemmas such invasions of privacy, unfair algorithms, theft of intellectual property, and creation of dangerous technology. User welfare must come first, privacy must be respected, diversity and inclusiveness must be encouraged in AI and algorithms, data usage must be transparent, and industry and regulatory rules must be followed in order to uphold ethical standards. Software engineering practices can be more ethically compliant by collaborating with stakeholders, providing ongoing education on ethical norms, and using ethical decision-making frameworks.

REFERENCES
PLP Lecture Slides
ACM Code of Ethics and Professional Conduct. Association for Computing Machinery (ACM)
IEEE Code of Ethics. Institute of Electrical and Electronics Engineers (IEEE).
Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
