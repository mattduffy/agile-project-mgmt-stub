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
  * planning
    - how long will an iteration last: 2 weeks, 4 weeks?
    - how will releases be conducted?
    - how will velocity be guaged?
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
Clearly establish the measure of functionality that is complete enough to be useful to the users, yet small enough to fit into the planned Iterations.  This is a group activity among the product owner, the stakeholders that will set the stage for early value delivery.  There are many trendy methods for collaboratively determining the MMP, some more complicated than others.  The process used is less important than correctly identifying the requirements and feature set that delivers the most value to the customer.

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
Creating a successful Backlog of user stories capable of delivering the high value features as early as possible takes practice.  One of the most effective ways to improve the quality of features delivered during iterations is to promote good discussions among team members.  Discussions facilitate the [deep](backlog-deep.md) understanding of the requirements needed to ensure the conditions of satisfaction (also known as acceptance criteria) are met.  User stories are the first step in meeting those conditions (see [user stories](story-user.md)).

Personas can be a very useful tool to promote good discusssion of the product requirements.  By taking the time to articulate the prototypical users of the product, the project team can see the product and features from the perspective of these identified users.  Asking questions like "How does Alice normally complete this task?" can result in a more thorough understanding of the requirement, leading to a better estimate of the level of effort required to produce it (see [personas](personas.md)).

Themes are another optional tool, like Personas, that can be used to enhance the quality of the Backlog.  Identifying the themes present in the Backlog can help the team prioritize the high value features to deliver in the early iterations.  The themes can be used in both Iteration and Release planning (see [themes](story-theme.md)).

Sometimes there are feature requirements that just cannot be adequately decomposed into user stories which are small enough to completely fit within a single Iteration following the INVEST approach.  This can be a sign that the requirement is not well understood, and therefore requires more discussion.  Or, it could just be a really large feature that needs to be treated as an [epic user story](story-epic.md).

##### Estimating the Level of Effort
Research has shown that too much emphasis on building accurate estimates too early can be harmful to the project.  Well documented and understood user stories make it possible to provide more accurate estimates of the work required to produce the prioritized features.  This is a key element of the Progressive Elaboration process, and helps make estimating more effective.  This only works, however, when the estimates are developed through a collaborative process, where those team members producing the features provide the estimates rather than a Traditional project manager.

  * Story Points and Relative Sizing 
    - team activity: create definition for the value of a story point
	  - team activity: create definition for 'done'
	  - team activity: begin affinity estimating for existing requirements 
  * determine Level of Effort method to use
    - Ideal Time
    - Wideband Delphi
    - Planning Poker
  * Budget and Costs
	  - Aggregate the Level of Effort by:
      - Story Points or
		  - Ideal Days
    - Convert aggregate Level of Effort into a schedule
	    - factor in team size
		  - required resources and availability
		  - other dependencies
	  - Aggregate costs over the schedule
	    - unburdend or burdened costs (see sample [burdened costs](burdened-costs.md))

##### The Feature Backlog
The Backlog is a dynamic component of the project plan.  Through the Progressive Elaboration approach, the Backlog will become much more detailed over the course of the project.  Changes in the product requirements may result in new user stories being added and existing stories being removed.  Because the Backlog is a product of team collaboration and stakeholder engagement, it can be considered a central and authoritative source of project progress.  The Backlog can actually make a very effective information radiator, used to quickly communicate current progress.

Prioritizing the Backlog will be a continuous process, with most of the work being done during the Iterations.  It is not expected that there be more than a high level first pass of prioritizing the newly developed user stories during Project Initiation.  A good strategy for developing a successful Backlog is to make it [DEEP](backlog-deep.md).

##### The Product Roadmap
The Product Roadmap, sometimes referred to as a Story Map, can be a useful tool to enhance the communication value of the Backlog by visually depicting how the user stories will be prioritized across the planned Iterations.  Product Roadmaps are often used in stakeholder communications and information radiators.  By presenting the Backlog in a time sequence perspective, roadmaps can easily convey high level details of the release goals, project dependencies and relative priorities of features.

For a sample view of a Product Roadmap laid out in Story Map fashion, see [Story Map](backlog-map.md).

### Planning the Project
A lot of work has been done up to this point, but it might feel like very little tangile project planning and execution has been done yet.  That should all change at this point.  Some key elements of the project have been established now: signoff from the sponsor, a clearly communicated vision of the product, a team approved definition of *Done*, and perhaps most important, a backlog full of well written user stories from which the *Minimally Marketable Product* will be built.  The next step is establish the release goals.  

* Create the Project Plan
  * the release plan
    * propose the release (or milestone) goals
    * are releases *date* driven or *functionality* driven?
  * the iteration plan
   - make time for Iteration 0
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

##### Release Planning


##### Iteration Planning


##### Iteration 0



