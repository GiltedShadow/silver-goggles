## Course Project Lab 2 of 6: Requirements and UML-OOAD Diagrams (60 points)

### Lab Overview
---

### Scenario/ Summary
---
This week, we have two very important tasks to prepare for the coming life cycle phases. First, we're preparing for the software design phase by more deeply exploring the requirements that we elicited last week based on the Business Problem Scenario. Second, we're preparing for the testing phase by figuring out how we're going to ensure that the requirements end up in the finished product. We may also need to update our project-level documents to reflect any changes that may occur.

### Deliverables
---
* Step 1: Write basic use case descriptions CEIS400-WK2-BasicUseCaseDescriptionTemplate-022215Links to an external site.
* Step 2: Create UML-OOAD use case and class diagrams and VOPC matrix 
  * Use case diagram [CEIS400-WK2-UML-OOAD-OverveiwSyntaxSummary-022215][^1]
  * Class diagram [CEIS400-WK2-UML-OOAD-ClassDiagramTips-022215][^1]
  * View of participating classes (VOPC) matrix [CEIS400-WK2-VOPC-Matrix-Example-InWord][^1]
  * Sequence and state chart (machine) diagrams are optional, as needed (optional)
* Step 3: Create test plan (IEEE 829 Standard Test Plan Draft) [CEIS400-WK2-IEEE-829-1998-TestPlan-Document-022215][^1]
* Step 4: Update project documents, as needed (not graded)
Individual team member cumulative time sheet

[CEIS400-IndividualProjectJournalTimeSheet-EXAMPLE-021915][^2] and [CEIS400-IndividualProjectJournalTimeSheet-TEMPLATE-021915][^2]


### Required Software
---
* Microsoft Word
  * Steps 1 and 4
* Microsoft Visio (Available at: https://aka.ms/devtoolsforteaching. Be sure to log in with your DeVry credentials. Then click Software under Learning resources. In the search box, search for Visio.)
  * Step 3
* Microsoft Project
  * Step 5 (also technically step 4)

### Lab Steps
---

### Step 1: Write Basic Use Case Descriptions
---
From the list of use case functions you identified in Lab 1, choose the five that you feel are the highest priority. (If you only identified five, then you'll be using them all.) Priority can be based on how frequently a feature will be used, how complex the development or testing effort may be, how visible the feature will be to the user, how much risk it poses to the project, and so on. Use cases that rank high in more than one of these factors would be excellent candidates for further exploration.

Once you have selected the highest-priority use cases, write a full description of each one. There is no single industry standard format for doing so, but use case descriptions typically include these sections in this order.

* Use Case Name: What shall we call this use case? Use the names you came up with last week.
* Requirements Explored: Which requirement numbers from last week are involved in this use case?
* Actors: Is this use case performed by any particular type of user, such as a supervisor or a customer? If not, you may just say User.
* Trigger: What specific action causes this use case to begin—clicking a specific button, logging in, selecting a specific item from a menu, and so on?
* Main Flow of Events: What steps take place in the interaction between the user and the system when everything goes as planned?
* Alternate Flow of Events: What other actions might the user or the system take that differ from the main course of actions described in the main flow?
* Exceptional Flow of Events: At what point(s) might something go wrong, and what happens then?

### Step 2: Create UML-OOAD Use Case and Class Diagrams
---
A common way to visually show the user's interactions with a system is to use a UML use case diagram. In other words, the use case diagram provides the system boundary through actors interacting with the use case functions. Create a diagram showing your five use cases, and if appropriate, their relationships to each other (such as "uses or includes" or "extends").

* The uses or includes relationship is common behavior between two use cases wherein one is the base use case and the other is the uses or includes use case. The arrowhead is on the uses or includes use case function.
* The extend relationship is optional behavior between two use cases wherein one is the base use case and the other is the extend use case. The arrowhead is on the base use case function.

Once the use case diagram is completed, the class diagram can be created based on the flow of events in the use case functions. Otherwise, your understanding of each use case function, basic descriptions, can be analyzed to determine potential classes for the class diagram. A more formal way to find classes is to analyze the nouns in each use case description, if you created a use case description for each use case function on your use case diagram.

The VOPC matrix can be completed with the list of use case functions in the left column, and the potential classes are identified for each use case function in the remaining columns to reconcile use cases to classes for requirements accuracy and traceability. See the example in the lesson.

The required UML-OOAD diagrams and deliverables for this step are as follows.

* Use Case Diagram
* Class Diagram
* View of Participating Classes (VOPC) Matrix (to reconcile use cases to classes for accurate requirements)
* Sequence and State Chart (Machine) Diagrams as Needed (optional)

### Step 3: Create Test Plan
---
Using the IEEE 829 Standard test plan outline, create a draft of an initial test plan based on the requirements gathered, business problem scenario, and completed UML-OOAD diagrams in Step 3. List any necessary assumptions to keep progressing toward the completion of the test plan.

### Step 4: Update Projecxt Documents as Needed (Not Graded)
---
Make any necessary updates to the project plan, business problem scenario, or IEEE SRS 830 to keep the quality of requirements traceable through the project.

### Step 5: Submit Deliverables
---
Create a zipped archive containing the following files.
1. Use Case Descriptions (minimum of three use case descriptions)
2. Use Case Diagram
3. Class Diagram
4. View of Participating Classes (VOPC) Matrix
5. Sequence and State Chart (Machine) Diagrams, as needed
6. IEEE 829 Standard Test Plan Draft
7. Updated Business Problem Scenario, IEEE SRS 830, and Project Plan, as needed
8. Individual Team Member Cumulative Time Sheet (see the template in the Lab 1 assignment)

Submit the zipped file for grading.

### Rubric
---
* Use Case Descriptions: 10 points
* Use Case Diagram: 15 points
* Class Diagram: 15 points
* View of Participating Classes (VOPC) Matrix: 5 points
* Sequence and State Chart (Machine) Diagrams, as needed
* IEEE 829 Standard Test Plan Draft: 10 points
* Updated Business Problem Scenario, IEEE SRS 830, and Project Plan, as needed
* Individual Team Member Cumulative Time Sheet (see the template link in the Lab 1 assignment): 5 points

[^1]: Note: all documents listed here can be found in the same folder
[^2]: Previous weeks documents can be found under Week One Documents
