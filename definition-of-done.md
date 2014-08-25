# What "Done" Looks Like

It is critical to the success of the project that then entire project staff, along with the stakeholders, agree on the definition of "done".  This is a discussion that should occur at least once per Iteration to reflect any changes in requirements that come about as a result of the adaptive planning process.

Below is a widely adopted guide to follow in software development projects that can be used as a sanity check before a user story is declared "done".

* ** **: Has the customer provided the "Conditions of Satisfaction" (aka User Acceptance tests)?
* **Tested**: Are all unit, integration, and customer acceptance tests finished?
* **Coded**: Has all the code been written?
* **Designed**: Has the code been refactored to the team's satisfaction?
* **Integrated**: Does the user story work from end to end (UI to the persistent storage) and fit into the rest of the software?
* **Builds**: Does the build script include the new code contributions?
* **Installs**: Does the build script include the user story in the automated installer?
* **Migrates**: Does the build script update the DB schema if necessary?  Does the installer migrate data when necessary?
* **Reviewed**: Have the customers reviewed the user story and confirmed that it meets their requirements/expectations?
* **Fixed**: Have all known defects been fixed or at least been scheduled as individual user stories?
* **Accepted**: Do the team and the stakeholders agree the user story is finished according to the Conditions of Satisfaction?
