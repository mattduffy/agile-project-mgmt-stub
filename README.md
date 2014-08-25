# Create a new agile project.

Use this process outline to help you kick-off a new Agile based project in a standardized and consistent manner.  Customize the outline as necessary to tailor the process to fit the needs of your organization or project.  Using this outline for each new project will help create a consistent practice and ensure all team members are familiar and comfortable in their roles.  It is not necessary to follow the process in the exact order the steps are presented in, but it tries to create a logical progression from less to more detail.  

### Feasibility
To be honest, many projects lack a formal feasibility process. There are plenty of reasons for this, and some common ones include: the project is considered too small to warrant this level of inspection, the project team lacks the necessary skills of a business analyst or maybe the feasibility work has already been performed.  While projects may certainly succeed despite the lack of a feasibility study, it is a good process to consider and gets easier with practice.  

Feasibility in Agile is very similar to what is done in Traditional project management.  The main difference is that the documentation tends to be lighter.  The same calculations can be used to build the business case.  A good place to start is with ROI, NPV, and IRR.

* Value-Based Analysis:
  * Create the business case
    * establish the high-level estimates (see [assessing project value](calculate-value.md))
      * Return On Investment
        * At what income value does this occur?
        * How long is the projected payback period?
      * Net Present Value
        * What is the expected future value of this project today?
      * Internal Rate of Return
        * useful for choosing between proposed projects when resources are constrained
  * Create the project vision
    * a group activity with the stakeholders
    * facilitates faster decision making and trust
    * provides team with a mantra, metaphor and motivation

### Tailoring the Agile Process
There are two simplistic yet prevailing views of adopting Agile methodologies: 1) Tailor the processes to fit the needs of your project or organization. 2) **Do Not** tailor the processess to fit the needs of your project or organization - the process works as designed.  It's okay to take either side of this debate; the main point is really just understanding the debate and how it may apply to your project.  I prefer to take a lighter meaning of the phrase *process tailoring* where the focus is on defining what I consider to be the metadata of the project, rather than the structural elements of management.  For example, if you choose to implement Scrum, metadata might include the time, location, and attendees of the Daily Stand-up meeting.  Whereas structural elements of this process might be frequency of the Daily Stand-up, or the 3 questions asked of each team member.  It is possible to change them, the reasons should be well thought out and agreed upon.  

* Define the Project Management approach for the project
  * Define and communicate the Project Management process requirements.
  * communicate, clearly and early, what methodologies are to be used:
    - Kanban and Scrum work well together and make up the rest of this guide.
    - XP, Feature Driven Development, Crystal, Lean Software Development are some other options.
  * establish process for estimating Level of Effort
    - what unit of measure will be used; Story Points, Ideal Days, Jelly Beans, etc?
    - how will Work In Progress limits be decided?
    - how will iteration velocity be initially estimated?
  * who will fill the team roles of product owner, coordinator, iteration planner, technical mentor, etc.?
  * what tools will be used: version control, testing framework, continuous integration, deployment manager, etc?
  * how will progress demos be conducted?

### Initiating the Project
Agile methodolies tend to center around the concept of deferring decisions when appropriate.  This is in contrast to Traditional PM methodolgies where a vast amount of time is spent up front, creating highly detailed baseline projections for time and cost.  This is where bulk of the early project planning takes place to create the project roadmap and goals.

##### Charter the project
By now, there should be sufficient information about the project to draft the Charter and make it official.  An Agile charter is a much simpler document than the charter from a traditionally managed project.  The charter is created as part of a group activity with the stakeholders.  See [charter sample](charter.md).
* answer the **W5H** questions:
  - What is the project about?
  - Why is the project being undertaken?
  - Who will be engaged in the project?
  - When will the project be undertaken?
  - Where will the project be undertaken?
  - How will the project be undertaken?
* define the product vision
  - create an elevator pitch
  - create a project tweet
  
##### Identify the Minimally Marketable Product
Clearly establish the measure of functionality that is complete enough to be useful to the users, yet small enough to fit into the planned Iteration concept.  This is a group activity among the product owner, the stakeholders, and the 

* Value-Based Decomposition and Prioritization:
  * elicit requirements from stakeholders
    - determine requirements gathering method:
      - facilitated feature workshops
      - focus groups
      - surveys, etc.
    - determine method used to prioritize the established requirements and features:
      - Remember the Future
      - Prune the Product Tree
      - Speedboat
      - Buy a Feature
      - Bang-for-the-Buck, etc.

##### Themes, Personas, and User Stories
Themes personas and user stories

##### Estimating the Level of Effort

* Estimating:
	* Story Points and Relative Sizing 
	  - team activity: create definition for the value of a story point
	  - team activity: create definition for 'done'
	  - team activity: begin affinity estimating for existing requirements 
  * determine Level of Effort method to use
    - Ideal Time
    - Wideband Delphi
    - Planning Poker
  * Budget and Costs
	  - Aggregate the LoE by:
      - Story Points or
		  - Ideal Days
    - Convert aggregate LoE into a schedule
	    - factor in team size
		  - required resources and availability
		  - other dependencies
	  - Aggregate costs over the schedule
	    - unburdend or burdened costs (see [burdened costs](burdened-costs.md))

* Create the Project Plan
  * Propose the milestone goals
  * Propose the release goals
  * Iteration plans
   - establish iteration plans
   - backlog grooming habits
   - risk assesments
	 - establish how risks will be quantified (EMV, time loss)
     - create a risk-adjusted backlog

| Plan                              | Goal       |
|:----------------------------------|-----------:|
| Project Total Size                | 185 points |
| Iteration Capacity                | 35 points  |
| Number of Iterations              | 185/35 = 6 |
| Release Every n Iterations        | 2          |
| - Weeks to Perform a Release      | 1          |
| - Weeks for Release Stabilization | 1          |
