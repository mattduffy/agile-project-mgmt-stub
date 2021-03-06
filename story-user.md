# Creating Agile User Stories
The **INVEST** acronym is frequently used to describe the key qualities of a successful user story.  By focusing on these attributes and using the template at the bottom of this page, you Backlog will be easier to groom.

### INVEST in Your User Stories
<b><u>I</u></b>ndependent
Each user story accepted into the Product Backlog should be independent from the other stories.  This can be difficult in practice, but it essential if we are to be able to reprioritize the Backlog for each Iteration.  We want to avoid having to drag any user stories into a release plan because they are dependent upon others.

<b><u>N</u></b>egotiable
The team should be able to discuss the meaning of a user story to accurately interpret the needs while still balancing the tradeoffs associated with cost and time to complete the story.  There may be numerous ways to solve the need of a user story and proper discussions between the team and the stakeholders should help zero in on the ideal solution.

<b><u>V</u></b>aluable
Every user story should provide measurable value to the customer.  It may be difficult to calculate that value, but it should be easy to understand.  The team should only be working on items that provide measurable value to the product.  

<b><u>E</u></b>stimatable
The team should be able to provide a workable estimate of time and cost for each user story.  If an estimate cannot be provided for a story, that is a sign that the requirement is not well understood and needs to be rethought.  If necessary, create a user story called "Estimate story X" to specifically provide the team with a _Spike_ to investigate the requirement further.

<b><u>S</u></b>mall
Small user stories tend to be better than larger ones.  They tend to be easier to estimate, and easier to understand when their scope and size are constrained.  It is generally advisable to keep the size of the user stories to within a single iteration.

<b><u>T</u></b>estable
The requirements and user stories should be clear enough that the testers and the product owners can easily determine when a feature fits the team-derived definition of "done".  

### A Sample User Story Format
Below is a simple template for formatting your user stories.  By design, users stories are intended to be high level descriptions of a requirement or feature.  Implementation details are purposely left out and are deferred to actual development time.  A successful user story will communicate a need to be filled for a particular segment of users while providing a brief comment on its value and most importantly, the acceptance criteria against which the feature's "done-ness" will be judged.

> As a *&lt;Role&gt;*, I want *&lt;Functionality&gt;*, so that *&lt;Business Benefits&gt;*.

See [personas.md](user personas) for a brief explanation on how creating user personas can help create successful user stories from the perspective of archetypal users.

See [decorcated users](decorated-users.md) for a brief explanation of how to enrich the quality of your user stories and provide a more detailed Feature Backlog.

See [story-theme.md](backlog themes) for a brief explanation of why to apply themes to the stories in your backlog.

### Template:

##### Story ID: &lt;auto-generated&gt;
##### Story Name: ___________________ 
##### Current Owner: ________________ 
##### Current Dev Stage: ____________ 
##### Stakeholder: __________________ 
##### Project Section: ______________ 
##### Level of Effort: ______________ 
##### Priority Set: _________________ 
##### Last Modified: ________________ 
##### Modified By: __________________ 
##### Risks Adjustment: _____________ 

##### Story:
As a prospective homebuyer, I want to see a complete and realistic estimate of the costs of owernship of a particular property purchased with a particular mortgage before signing a contract, so that I can directly compare its competitive value against other loans and / or other properties.

##### Risks Identified: 
  * @risk1: description of identified risk.
  * @risk2: description of identified risk.

##### Conditions of Satisfaction:
Criteria 1
> **Given** an active user account is created, the user logs in, and has no loan profiles created,
> **When** a logged-in user clicks on New Profile, 
> **Then** a form is displayed to enter new loan data which can be saved, viewed, edited or deleted.

Criteria 2:
> **Given** a full and accurate reporting of the costs associated with purchasing a particular property,
> **When** a particular loan profile has been offered,
> **Then** the user can determine the competitive value of the contract.
