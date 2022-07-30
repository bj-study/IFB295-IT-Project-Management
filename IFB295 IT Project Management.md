# IFB295 Study Guide | 2022 Semester 2

Mark Walpole | Notes for IAB330 at the Queensland University of Technology

<hr />

<h1>Table of Contents</h1>
<ul>
	<li><a href="#IFB295">IFB295: IT Project Management</a></li>
	<ul>
		<li><a href="#week1">Week 1</a>: Project Management, User Stories, Scrum, and Teamwork</li>
		<li><a href="#week2">Week 2</a>: Why Agile? Scrum framework, principles. and roles</li>
		<li><a href="#week3">Week 3</a>: </li>
		<li><a href="#week4">Week 4</a>: </li>
		<li><a href="#week5">Week 5</a>: </li>
		<li><a href="#week6">Week 6</a>: </li>
		<li><a href="#week7">Week 7</a>: </li>
		<li><a href="#week8">Week 8</a>: </li>
		<li><a href="#week9">Week 9</a>: </li>
		<li><a href="#week10">Week 10</a>: </li>
		<li><a href="#week11">Week 11</a>: </li>
		<li><a href="#week12">Week 12</a>: </li>
		<li><a href="#week13">Week 13</a>: </li>
	</ul>
</ul>

<hr /> 

<h1 id="IFB295">IFB295: IT Project Management</h1>
<p>In your information technology career, you will participate in and then lead project teams that are expected to deliver real benefits to stakeholders. This unit builds on your previous studies of earlier units to define a high-level solution by using a range of approaches of project management methodologies and frameworks. You will enhance your learning of these approaches (Agile, PRINCE2 etc.) by practicing it collaboratively with other students. To be successful in a complex environment, you need to employ appropriate project management strategies, tools and techniques for a given context. This unit provides you with the necessary knowledge and skills to enable you to effectively manage your project in the IFB398 Capstone Project (Phase 1) and IFB399 Capstone Project (Phase 2) and to be prepared for a project environment in industry. </p>

<hr /> 

<h2 id="week1">Week 1: Project Management, User Stories, Scrum, and Teamwork</h2>

### Project Management
Project management is the act of planning, organising and creating procedures and protocols to ensure that a project achieves it's goals, is delivered on time and is of a high quality.

### Terminology
- Methodology
  - A methodology is a set of methods, principles and rules that follow concepts such as paradigm, theoretical model, phases and techniques.
- Framework
  - A framework is a basic structure underlying a system, concept, or text
- Artifact
  - A by-product produced during the development. This could be a use case diagram, class diagram or other design documents that help describe the design and architecture

### Scrum
Scrum is a framework designed to help teams work together. Scrum encourages development teams to learn through different experiences, self-organise themselves while working on a problem, and reflect on their progress, wins, and losses in an attempt to continuously improve themselves.

### Scrum Roles and Responsibilities
- Product Owner
  - This is the owner of the product. They are responsible for optimising value, ordering the product backlog in priority and product incrementing
- Scrum Team
  - The scrum team is the team working on the project. They are responsible for self-origanisation, cross-functional, ordering and choosing which items appear in the sprint backlog
- Scrum Master
  - The scrum master is the leader of the scrum team. They are responsible for coaching, training, and supporting the scrum team.

### User Stories
User stories are short informal descriptions explaining a software feature from the perspective of an end user. It's purpose is to demonstrate how the software or a feature will provide value to the customer. User stories also help define the acceptance criteria of a particular feature.

For example:
> As a [ role ], I want to [ do / see / change something ] so that [ outcome ].

### INVEST
All user stories should follow the INVEST acronym.

- Independent
  - User stories should be independent as dependencies can make planning, prioritisation and estimation difficult
- Negotiable
  - User story details should be worked out in a conversation between the customer and the developer
- Valuable
  - The user story must provide some sort of value to the customer. User stories should be written with the customer to ensure this
- Estimable
  - The feature or product the user story is crafted around should be estimable. These estimates are then used in the initial prioritisastion and planning of the project 
- Small
  - User stories should be short and sweet. They must only represent a few days in person effort as this allows them to be more precise and accurate
- Testable
  - User stories should be able to be crafted into acceptance criteria. We can't develop things we can't test

### Acceptance Criteria
Acceptance criteria is the criteria that must be met before we can say a feature is completed. They should follow a Given-When-Then template such that:
- Given some context
- When some action is carried out
- Then a particular set of observable consequences

For example:
> As a lecturer, I want to be able to see a list of all students enrolled in my classes so that I can see class lists and numbers enrolled.

Acceptance Criteria:
- **Given**: I have a "Show Classes" link displayed for the classes I lecture
- **When**: I click on "Show Classes"
- **Then**: The system should display the list of classes together with class activity, class numbers, day and time, and room where the class is held

### Epics
Epics are large user stories that are too big to implement in a reasonable timeframe. These types of user stories are split into smaller separate stories to help spread and breakdown the workload.

<br />

<h2 id="week2">Week 2: Why Agile? Scrum framework, principles. and roles</h2>

### Agile Development?
Agile development focuses on repeating the waterfall development cycle for each feature working in 'sprints' that focus more on iterative and incremental development. Iterative and incremental development is the process of starting and finishing small chunks of the given problem at any one time. One of the major benefits of this is that the customer is constantly involved in the decision making and can slowly watch the solution be developed. 

Developing in this iterative and incremental manner allows us to easily break down the problem and helps us avoid making sub-optimal design choices early on based on limited knowledge and understanding. Another benefit to this design process is that we have sections of working code at the end of each iteration allowing us to show managers and customers. This allows the development team know they are doing the right thing and gain active feedback.

### Scrum 
The scrum framework has 3 main principles:
1. Optimise value: Incrementally deliver value each sprint (every 30 days or less)
2. Optimise productivity: Foster self-organising teams
3. Optimnise predictability: Use empirical process control. This means that things are done in a highly visible manner e.g. Burndown charts

### Product Backlog
A product backlog is a backlog of items that consist of the user stories, an estimated effort, and a priority order. For example:

| Id | Priority | Backlog Item | Effort |
|--|--|--|--|
| 412 | 1 | Allow a guest to make a reservation | 4 | 
| 414 | 2 | Allow a guest to cancel a reservation | 2 |
| 415 | 3 | Allow a guest to change the dates of a reservation | 2 |
| 417 | 4 | Allow an employee to run RevPAR reports | 8 |
| ... |

### Product Backlog Item (PBI)
A product backlog item is an item or task that goes into the product backlog. These contain important information about the PBI such as a description, reproduction steps (in the case of a bug), the acceptance criteria, and any discussions currently occuring about it such as updates or changes.

### Sprint Ceremonies
A sprint is a defined period of time where a set number of PBI's are estimated, assigned and then expected to be completed. A sprint can be done in 1-4 week periods but once a time period is chosen it's unlikely to change. Each sprint consists of 4 main events:
1. Sprint planning (1-4 hours)
2. Daily scrum meetings (15 minutes)
3. Sprint review (1-4 hours)
4. Sprint retrospective (1-3 hours)

### Sprint Planning
Sprint planning occurs at the start of each sprint. It's in this meeting that the total effort for the sprint is calculated (the total amount of working hours the team can provide) and which PBI's are assigned to the sprint. The total PBI's effort cannot exceed the maximum sprint effort. The PBI's brought into the sprint are now reviewed to make sure all the information makes sense to the team and that all required information is there to complete it.

### Daily Scrum
Daily scrums are generally the first thing to happen each day and last for around 15 minutes. In these meetings the development team and the scrum master get together and each member describes:
1. What they did yesterday
2. What they plan to do today
3. If anything is blocking or preventing them from meeting their sprint goal
4. Any clarifications needed for them to go about their day

### Sprint Review
A sprint review happens on the last day of the current sprint. In this meeting there are a variety of things mentioned:
1. The completed PBI's are walked through and explained (demonstrate the new working features or things that got done)
2. Any PBI's that weren't completed are talked about (why didn't they get finished) 
3. How many times code was deployed to production 
4. If all the completed PBI's comply with the definition of done (a document describing what needs to occur for a PBI to be marked as complete)
5. The Burndown chart is looked at and that information is taken and used in how the next sprint is planned e.g. how many items the team can take on

### Sprint Retro
The sprint retrospective is a meeting where the development team reflect on the previous sprint and talk about:
- What went well
- What didn't go well
- What can be improved
- What lessons were learnt

### Product Backlog Item Prioritisation
The product owner will generally set an order in which the PBI's must be completed in. When setting priorities it's good to follow the acronym MoSCoW:
- Must have: The customer would expect all of these items to be implemented
- Should have: The customer would expect most of these items to be implemented
- Could have: If there is capacity within the project and resources available these will be implemented
- Won't have: It is unlikely that these items will be implemented

### Story Estimation
Each PBI (or story point) is initially estimated. This is done for a variety of reasons such as:
- To get an initial feel for the project cost
- Determine if the project is still feasible and whether development should continue 
- Reduce, discard and re-prioritise PBI's based on cost

Each PBI is estimated in effort (not units of time). This means, for example, in a team of five people, suppose each member spends 10 hours a week on the project. This would mean that, with each person spending 2 hours a day, a total effort of 10 hours a day, or 50 hours a week, would be the estimated sprint effort. It's important to be consistent when labelling a PBI's effort as all PBI's with that estimated effort should require the same amount of effort. This allows all PBI's with the same effort to be exchangeable with each other.

There's many ways of labelling an estimate for a PBI:
- Powers of 2 (2, 4, 8, 16)
- T-shirt sizes (S, M, L, XL)
- Fibonacci scale
- and more

Planning poker is a game to help estimate the effort for each PBI. In this game each player has a set of cards (1, 2, 4, 8, 16, 32), one team member reads out the user story and each team member must place a card upside down with their estimation of the required effort. Once all cards are place they are revealed and the most common estimate becomes the effort. Everyone must then explain why their estimate is like such and whether they agree with the others or not.