## Course Project Lab 1 of 6: Project Scope and High-Level Requirements (60 points)

### Scenario/Summary
---
This week, we will begin the process of engineering a solution to a business problem scenario. Once we have defined the problem, our next task will be to get an idea of the project's scope, so we will begin by eliciting functional requirements and documenting them. As we do so, we will attempt to identify potential use cases to help us understand the types of things that the users will expect to do with the new system.

### Deliverables
---
* Step 1: Detailed description of a business problem scenario [CEIS400-BusinessProblemScenario-TEMPLATE-021915][^1]
* Step 2: Elicit high-level requirements (not graded)
* Step 3: Initial draft of a software requirements specification (SRS) [CEIS400-IEEE-830-SRS-Outline-TEMPLATE-021915.docxCEIS400-IEEE-830-SRS-Outline-TEMPLATE-021915][^1]
* Step 4: Initial list of use cases
* Step 5: Project plan (All lab assignments are activities and tasks within the traditional SDLC phases as the Work Breakdown Structure (WBS))
Individual team member cumulative time sheet [CEIS400-IndividualProjectJournalTimeSheet-EXAMPLE-021915][^1] and [CEIS400-IndividualProjectJournalTimeSheet-TEMPLATE-021915][^1]

### Required Software
---
* Microsoft Word
  * Steps 1, 3, and 4
* Microsoft Project
  * Step 5
Access the software at <https://lab.devry.edu>.

Lab Steps
---

### Step 1: Define the Business Problem Scenario
---

If a business problem scenario has already been provided for your team (see the Course Project Overview in the Introduction & Resources Module), then skip to Step 2. Otherwise, your team must come up with one of its own. Remember though, whether your team has been assigned a business problem scenario or your team must come up with a business problem scenario itself, your team is still responsible for filling out the Business Problem Scenario template.

Also, please remember that your group should have a team leader. The team leader's responsibilities per week include organizing the team's overall efforts, gathering each team member's Individual Project Journal Time Sheet Excel spreadsheet, and submitting all documents as a zip file. Make sure to inform your professor who your team leader is as soon as possible.

Think of a new software product, service, or system that you would like to engineer. Any type of program on any type of computing device may be used, as long as it is substantial enough to justify a semiformal software engineering process. For instance, you may want to design a new point-of-sale system for convenience stores, a shopping cart for online retailers, a video game for mobile devices, a social network specializing in your favorite hobby or career, or so forth. Perhaps you can get ideas from friends or relatives by asking them what kind of technology would help them in their lives or jobs. Keep in mind that you will be designing, developing, and testing a functional prototype of this system later in the course.

Once you have a clear vision of the software system you would like to develop, document it as thoroughly as possible using the Business Problem Scenario template. The template will help you figure out what information you need to provide and how to organize it.

### Step 2: Elicit High-Level Requirements
---

This step is essentially a brainstorm in which we are just trying to gather as much information as we possibly can about the system we will be designing.

Read your Business Problem Scenario carefully. As you do, pay attention to anything that implies features, functions, or capabilities that the system will be expected to have, and write them down on scratch paper, a whiteboard, a text file, or whatever is easy and convenient for you. Regardless of how you choose to record your findings, this will become the input to Step 3 below.
Some helpful tips follow.

* Object-oriented analysis (OOA) techniques can be most effective at generating an initial list of requirements. Look for nouns (people, places, things) and verbs (actions) to get an idea of what elements may exist and the behaviors that they may perform.
* User-centered design (UCD) is another area from which we can borrow ideas. Pay special attention to things that require the user to perform an action or provide input or things that show output or give feedback to the user.
* A TOR chart can be an incredibly handy artifact for capturing this information quickly and in a somewhat organized manner. TOR stands for tasks-objects-remarks. It's a simple table with three columns that are used as follows.
  * The first column is tasks. Every time you see an action verb phrase, write it in this column.
  * The second column is objects. For each task in the first column, list every noun that is associated with it in any way. This includes objects that perform the task, objects that are affected by the task, and objects that may somehow influence the task.
  * The third column is remarks. For our purposes here, you don't necessarily need to use this column, but you may if you find it helpful.

### Step 3: Create the SRS
---
Now you should have an idea of what the system will contain and what features it will have. The next step is to organize and formalize this information in a document that will serve as the basis for much of the work to follow. Fortunately, we have a document template that was designed for just that purpose: IEEE Standard 830 is a professional, industry-standard template for a software requirements specification (SRS).
We are not going to complete the entire document right now. We're just going to fill in what we know so far and then come back for the rest later.
  1. Download the SRS template.
  2. On the cover page:
* Name the project or the product.
* List the team members' names.
* Include the phrase Software Requirements Specification.
* Include a version number that you can update later as changes are made to the document.
* On the Revisions page, create a table with four columns.
  * Label the first column Date. This column will contain the dates that revisions were made.
  * Label the second column Revision. This column will list the version numbers that the document goes through as revisions are made.
  * Label the third column Description. This column will contain a brief description of the revision, such as what was changed or the reason for the change.
  * Label the fourth column Author. This column will contain the name of the author who made the revision.
* Enter this information as the first entry in the table of revisions.
  * Date: <today's date>
  * Revision: 1.0 (or whatever version number you put on the title page)
  * Description: Initial draft
  * Author: \<the name of the student who is typing it>
* On the Table of Contents page, use the table of contents feature in Word to insert a table of contents. It won't show much yet, but later you can tell Word to update it after we fill in the other sections.
* In Section 2.1 (Product Perspective), summarize the software that you intend to create. You may be able to copy this paragraph from the Business Problem Scenario.
* In Section 3.1 (External Interface Requirements), describe how you expect the system to communicate with the outside world. The sections might be used as follows, though not all sections will apply to all software systems.
  * User interfaces: How will the software communicate with users? What screens, devices, or views will provide the required input and output?
  * Hardware interfaces: What additional devices will the system need to communicate with, if any?
  * Software interfaces: If the system will need to interact with other programs, what technology will enable this to happen?
  * Communications protocols: If the software needs to communicate over a network, what protocols will it use to do so?
* Section 2.2 (Software Product Features) is where the most essential content of the document will be. In this section, you will list all of the requirements you have identified so far. For each requirement statement, do the following.
  * Assign a unique number to the requirement. This will allow us to trace the requirement through the various phases of the software development life cycle.
  * State the requirement in a clear, unambiguous way. A best practice for writing requirements statements is to begin with a phrase such as "The system shall..." and then state in a clear and simple way what the system will do. You may also be more specific in some cases and say things such as "The user interface shall..." or "The security subsystem shall..." and so forth.
* Section 2.3 (Software System Attributes) can be left empty for now. This section is for nonfunctional requirements (NFR), which we will discuss later in the course. We will return to complete this section in a later lab. For now, just put in the section title as a placeholder.
* If your system will require a database or other persistent data store, briefly describe in Section 2.4 (Database Requirements) what the data store will need to do for the software.

### Step 4: Identify Use Case
---

A use case describes a way that a user will interact with a feature of the system. Later in the course, we will elaborate on use cases to gain an understanding of how the system is expected to behave in response to user interaction. For now, we just want to make a list of the things that the user will be doing. 
A best practice for naming use cases is to follow a format such as below. 

\<user role> \<action verb> \<object>

Some examples are as follows. 
* User creates profile.
* Customer enters payment information.
* Player launches game.
* Manager generates report.
In a new document, provide at least five use cases. This should be easily attainable for even the simplest software applications.

### Step 5: Create the Project Plan[^2]
---

Individual cumulative time sheets for detail team member contributions must be consistent with the project plan assignments and submitted with each lab assignment. See the Individual Team Member Time Sheet template. 

Individual cumulative time sheets for detail team member contributions must be consistent with the project plan assignments and submitted with each lab assignment. See the Individual Team Member Time Sheet template. 

The Work Breakdown Structure (WBS—phases, activities, and tasks) is based on the four traditional SDLC phases outlined in the Week 1 Lesson. For example, the first SDLC phase will be planning. The creation of the Week 1 Lab assignment deliverables will be the activities within the planning phase. You can go to the task level, if necessary. Also, be sure to add any additional activities or tasks you think are necessary in each phase, such as research, reviews, team status meetings, and so forth. See the six lab assignment sections for details on the deliverables (potential activities).


### MS Project Key Creation Steps
---

  1. Create the four SDLC phases first (Planning, Analysis, Design, and Implementation) to start off the WBS.
  2. Create activities from all six lab assignments within the appropriate SDLC phase. You should be able to map each lab assignment to the correct SDLC phase by reading the lab assignment description. Again, see the Week 1 Lesson for the SDLC overview. If you prefer to use the week as the activities and lab assignment deliverables as the task, that can work, as long as team member resources are assigned on the lab assignment deliverable level.
  3. The team leader must assign one or more team members (resources) to specific activity deliverables in each lab assignment.
  4. Create estimate durations for each activity, from 1 to 8 days (standard weekly grading period due dates for the lab assignment).
  5. Indicate a few dependencies (predecessors) among activities (or tasks) within each SDLC phase.
The MS project plan can be updated every week, but the final version must be submitted for grading in Week 8. All team members should know what they are assigned to do each week.

### Step 6: Submit Deliverables
---
Create a zipped archive containing the following files.
  1. Business Problem Scenario (see template provided)
  2. Software requirements specification
  3. List of use cases
  4. MS Project plan (.mpp file). Note: Use the four traditional SDLC phases and all lab assignments as activities within the appropriate phase.
  5. Individual Team Member Cumulative Time Sheet (see template provided)
Submit the zip file for grading

### Rubric
---
* Business Problem Scenario: 15 points
* Software Requirements Specification: 15 points
* List of Use Cases: 15 points
* MS Project Plan: 10 points
* Individual Team Member Cumulative Time Sheet: 5 points

[^1]: Note: all documents listed here can be found in the same folder
[^2]: accompanied video describes creating project plans on Microsoft project
