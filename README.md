[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15220912&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering: (Source: techtarget.com)
Answer: Software engineering is the branch of computer science that deals with the design, development, testing, and maintenance of software applications

What is software engineering, and how does it differ from traditional programming?
Software Development Life Cycle (SDLC): (Source: techtarget.com)
Answer: Software engineering is the process of developing, testing and deploying computer applications to solve real-world problems by adhering to a set of engineering principles and best practices. 
- Whereas traditional programming focuses on writing code to solve a specific problem or create a specific program. Software engineering focuses on designing, testing, and maintaining software systems.
- Traditional programming emphasizes technical skills, such as proficiency in a programming language. Whereas software engineering emphasizes a systemic approach, considering factors like scalability, reliability, and maintainability.
- Traditional programming often involves a solo effort or a small team. Software engineering often involves collaboration with a larger team, including non-technical stakeholders.
- Traditional programming typically has a short-term focus, with a specific deadline or deliverable. software engineering has a long-term focus, with consideration for the software's entire lifecycle.

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Agile vs. Waterfall Models: (Source: metaai)
Answer: SDLC is a process that development teams use to create awesome software that's top notch in terms of quality, cost effectiveness, and efficiency.
7 phases of SDLC:
1. Planning & analysis: Examine the requirements, defining the problems to be solved, and outlining the overall scope and constraints of the project.
2. Requirements: Is the critical phase of converting the information gathered during the planning and analysis phase into clear requirements for the development team.
3. Design: Here we create a detailed design of the software, including its architecture, user interface, and system specifications.
4. Development: The development phase where the development team members divide the project into software modules and turn the software requirement into code that makes the product.
5. Testing: Verify that the software meets the requirements and works as expected, identifying and fixing defects.
6. Release the software to the production environment, making it available to users.
7. Maintenance: The maintenance phase is the last phase of the SDLC where the software is supported and updated addressing issues, adding new features and ensuring continued performance.

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Requirements Engineering:
Answer: (Source: Simplilearn.com)
Starting with Waterfall method:
- Has a linear, sequential approach.
- Phases are completed in a specific order, with each phase depending on the previous one.
- Requirements are gathered and defined before development begins.
- Development, testing, and deployment are separate phases.
- Changes are difficult and costly to implement once project is underway.
- Emphasis on predictability and stability.
Agile Method:
- An interactive and incremental approach.
- Phases are flexible and overlapping.
- Requirements are continuously gathered and redefined throughout the project.
- Development, testing, and deployment are intergrated and ongoing.
- Changes are embraced and easily accommodated
- Emphasis on adaptability and delivery.
Key differences:
- Waterfall is plan-driven, while Agile is value driven
- Waterfall is rigid, while Agile is flexible.
- Waterfall focuses on predictability, while Agile focuses on adaptability.
Scenarios each method is needed.
Starting with Waterfall in what scenarios it might be used:
1. Simple, well-defined projects: Requirements are clear, and changes are unlikely.
2. Regulated industries: Compliance and auditing require a predictable, traceable approach.
3. Legacy system maintenance: Updates and fixes for existing systems with established requirements.
4. Small teams or individual projects: Easy to manage and communicate within a small team.
Agile method:
1. Complex, uncertain projects: Requirements evolve or are unclear, and adaptability is crucial.
2. Innovative or experimental projects: Emphasis on rapid prototyping and iterative refinement.
3. Customer-facing applications: User feedback and continuous improvement are essential.
4. Large, distributed teams: Collaboration and flexibility are necessary for success.


What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Software Design Principles:
Answer: (Source - GeeksforGeeks.org)
Requirements Engineering is the process of identifying, eliciting, analyzing, valiadating, and managing the needs and expectations of stakeholders for a system software.
Process of Requirements engineering:
- Feasibility study: This determines whether the project is practical.
- Requirements elicitation: This involves gathering information about the project from sources like customers, business manuals, and other stakeholders.
- Requirements specification: This step involves documenting the requirements gathered in the elicitation process.
- Requirements verification and validation: This ensures that the requirements are complete, consistent, and accurate.
- Requirements management: This involves managing the requirements throughout the software development life cycle.
Importance of Requirements engineering:
- Ensuring software meets user needs by gathering detailed requirements from stakeholders and end-users and translating them into technical specifications that guide the development process
- Identifying constraints and limitations that might affect the project, including technical constraints, regulatory requirements, and budgetary limitations.
- Setting a solid foundation for the subsequent phases of the SDLC to reduce the risk of developing a system that fails to meet user expectations or requires significant rework.
- Managing changes in the project scope.
- Collaboration and communication among team members and stakeholders.
- Documenting the requirements to understand, work together, and find information throughout the project.
- Requirement prioritization and validation to focus on the most critical aspects of the project and manage resources more effectively.
- Regular reviews and updates to account for any changes, new information, or stakeholder feedback and ensure that the project stays on track and meets its objectives.

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Testing in Software Engineering: (Source: ituonline.com)
Answer: The core concept of modularity involves encapsulating information within a module, exposing only what is necessary through a well-designed interface and hiding the rest. This separation of concerns ensures that individual modules can operate independently while interacting through strictly defined interfaces.
Modularity in software design improves maintainainability and scalability in several ways:
- Maintainability: Changes in one module typically do not affect others, making bugs easier to track down and fix without risking other parts of the system.
- Reusability: Modules designed for one project can often be used in another, saving development time and reducing errors by reusing proven code.
- Scalability: Modular systems can be scaled more readily by adding new modules or enhancing existing ones without impacting the rest of the system.
- Parallel Development: Different teams can work on different modules simultaneously, decreasing development time.
- Better code organization: Modularity promotes better code organization and readability, making it easier for developers to understand and work with code.
- Easier debugging: With modularity debugging becomes easier as issues can be isolated to specific modules, reducing the complexity of debugging.
- Parallel development: That is working on multiple projects or features at the same time.

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
Version Control Systems:
Answer: 
1. Unit Testing:
- The first level of testing. This testing is the most basic type of testing done by developers before handing the software/product to the testing team.  Unit testing is a type of software testing in which individual units or components of the software are tested.
2. Integration Testing:
- The second level of testing. The testers rather than developers conduct this testing. Integration testing is a type of software testing in which individual software components (modules) are logically integrated (combined) and tested as a group.
3. System Testing: 
- The third level of testing. This level of tests assists you in identifying bugs and challenges while ensuring that the software will meet all specific requirements. System testing is software testing in which all components are tested together (as a whole) to ensure that the final product meets the specified requirements.
4. Acceptance Testing:
- Acceptance testing is the last level of testing. this level is testing in broad scope, ranging from simply finding spelling and cosmetic errors to discovering bugs that might produce a significant error in the software.
- Acceptance testing is a type of software testing that determines whether or not the software should be released to the public.
Software testing is imperative, as it identifies any issues and defects with the written code so they can be fixed before the software product is delivered.

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Software Project Management:
Source (reddit.com)
Answer: Version control is a system that tracks the progress of code across the software development lifecycle and its multiple iterations - which maintains a record of every change complete with authorship, timestap, and other details - and also aids in managing change.
Importants of version control systems:
- Facilitates collaborative coding.
- Tracks Changes to codebase.
- Enhances code organization.
- Enables seamless team collaboration.
- Improves code quality and productivity
Examples of popular version control systems:
1. Github
- An open source version control system that features local branching, multiple workflows, and convenient staging areas.
2. Gitlab
- Comes with a lot of handy features like an integrated project, project website, etc
3. Beanstalk
- Ideal for those who work from remote places. This software is based on browser and cloud, allowing users to code, commit, review and deploy using a browser.
4. PerForce
- PerForce delivers the version control capabilities through its HelixCore. It is a security solution that protects the most valuable assests. HelixCore allows you to track the code changes accurately and facilitates a complete Git ecosystem.
5. AWS CodeCommit
- Is a managed version control system that hosts secure and scalable private Git repositories. AWS inegration provides access to several useful plugins from AWS partners, which helps in Software development.
6. Bitbucket
- The main features of Bitbucket are code branches, in-line commenting and discussions, and pull requests.

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Software Maintenance:
Source (thedevpost.com)
Answer: A software project manager is responsible for leading a team of software developers and ensuring that software projects are completed on time, within budget, and to the satisfaction of the stakeholders.
They are responsible for planning, executing, and closing projects. This involves defining project scope, creating schedules, allocating resources, managing risks, and monitoring progress.
The project manager is also responsible for communicating with stakeholders, including clients, management, and team members, to ensure everyone is on the same page.
Some of the challenges faced by software project manager:
1. Unclear and undefined expectations.
2. Time constraint.
3. Changing project requirements and priorities.
4. Poor communication.
5. Skills management.
6. Changing technologies.
7. Keeping everyone on the same page.
8. Motivating team members.
9. Steep learning curves.
10. Project cancellation.
11. Estimation.
12. High competiition.
13. Upgrading to a new system.
14. Quality testing.
15. Managing risks.

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Ethical Considerations in Software Engineering:
Source (koombea.com, cpl.thalesgroup.com)
Answer: Software maintenance is the process of changing, modifying, and updating software to keep up with customer needs.
The four types of software maintenance are:
1. Corrective:
- Corrective software maintenance identifies errors, bugs, and faults and takes the necessary steps to correct them.
2. Adaptive:
- Adaptive software maintenance handles the shifting technological landscape and ensures that your software product is up to date with the latest technologies, versions, libraries, etc.
3. Preventative:
- Preventative software maintenance looks for issues in the software and resolves them before they can become issues.
4. Perfective:
- Perfective software maintenance deals with improving a software product's current features and functionality.
Maintenance an essential part of the software lifecycle because without maintenance, any software will be obsolete and essentially useless over time.

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Answer: Software engineers may face: (Source: fullscale.io)
1. Data privacy.
2. Accessibility
3. Addictive Design.
4. Algorithmic bias.
5. Software security
6. Wrong priorities
Software engineers can ensure they adhere to ethical standards in their work by:
1. Being Honest
2. Being proactive
3. Being Accountable
4. Be a responsible citizen

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
