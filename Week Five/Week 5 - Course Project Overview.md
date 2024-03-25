## Course Project Lab 4 of 6: Software Design and Construction (70 points)

### Lab Overview
---


### Scenario/Summary
---
This week, we will be diving into the very heart of software engineering—the activities of design and construction. First, you are going to perform a component-level design for the primary functionality of your system. This will specify how the code will be created, how it will be structured, and how it will behave. Then you are going to begin the process of implementing the design by constructing the code that will be completed as part of next week's Course Project Lab.

### Deliverables
---
* Step 1: Create a software design.
* Step 2: Create a software design description (SDD) document (graded).
* Step 3: Prepare for construction.
* Step 4: Construct the architecture (graded).
* Step 5: Begin constructing the components (graded).
* Step 6: Update project documents, as needed.
* Step 7: Submit deliverables.

### Required Software
---
* Microsoft Visio (Available at: https://aka.ms/devtoolsforteaching. Be sure to log in with your DeVry credentials. Then click Software under Learning resources. In the search box, search for Visio.)
    * Step 1
* Microsoft Word
    * Steps 1, 2, and 6
* Microsoft visual Studio
    * Steps 4 and 5
* Microsoft Project
    * Step 6

All the software is available is at [lab.devry](https://lab.devry.edu/)

### Lab Steps
---

### Step 1: Create a Sopftware Design
---
Review the requirements in your SRS. These describe the objectives of your design and construction work. Your first task is to create a design or set of designs that will enable the implementation of these requirements through the activity of programming. As you work through these activities, actively look for opportunities to apply design patterns. You will be expected to implement at least two in your final construction.

##### 1. Perform an Object-Oriented Analysis (OOA) of the Requirements

Before we can formally begin a design, we must perform an analysis to gain an understanding of the elements involved and determine the relationships between them. This information can come from several sources, the most effective of which are the following.

* The software requirements specification, which describes all of the intended behaviors (functional requirements) and quality attributes (nonfunctional requirements) of the system
* Use case descriptions, which provide scenarios mentioning objects and their required tasks
* The TOR chart if you chose to create one in the Week 1 Course Project Lab, which lists tasks and objects that are potential candidates for functions and classes, respectively
* Any diagrams that you may have created to help you understand and visualize the requirements

##### 2. Create a Static Object-Oriented Design (OOD) View

Once you have identified the candidate classes, document their static structures in a UML class diagram as follows.

* Each class should be represented with the appropriate UML classifier.
* Whatever operations exist in the system should be added to the operations section in the appropriate classes.
* Whatever relevant attributes you encounter should be added to the attributes section in the appropriate classes.
* Whenever you discover a relationship between classes, connect them with the appropriate UML connector to indicate inheritance, composition, dependency, and so forth.

##### 3. Create a Dynamic OOD View

For each of the major operations in the system, use UML diagrams to construct a dynamic model of how the system will perform them. Many diagrams can serve this purpose; sequence diagrams, activity diagrams, collaboration diagrams, and state diagrams all represent behavioral aspects of the system.

##### 4.  Look for Design Patterns

If you have not already identified a need for design patterns, see if you can find any patterns that might help to improve your design. The patterns listed in last week's lesson are a good place to start, but if those patterns do not fit, there are many books and online resources that cover design patterns in much greater detail.

Here are some questions that may help you get started.

* Do you have any objects that change their behavior in response to an event? Consider using the state pattern.
* Do you have a large number of dependencies among several classes? Consider the façade pattern or the mediator pattern.
* Do you have any objects that are created or initialized differently based on some variation in the system? Consider a factory pattern.
* Do you have an object that will be the only one of its kind? Consider the Singleton pattern.
* Do you have a function or process that might differ only slightly from one subclass to another? Consider the template method pattern.

This list is just intended to get you thinking about design patterns. Remember that there are many more, and you may use whatever patterns that make sense in your system. Include at least two design patterns in your design, and be sure to explain them in writing.

##### 5. Review the Design for Quality

Compare your design against the list of design principles from the Week 4 Lesson. Are there any principles that your design is violating? It may not be possible to satisfy all of them because of the trade-offs involved, but if you can follow one without violating others, then that is usually the right decision.

### Step 2: Create a Software Design Description (SDD) Document
---
Now you will need a place to store and organize your design work. IEEE Standard 1016 gives us a customizable software design description template that we can modify to suit the purpose of any type of software project.

The following is one possible template, loosely inspired by IEEE Standard 1016, that should work well for the projects in this course. Most of the sections in this template are going to be short, and several are going to be repeats of things you have already written in previous labs. The area that is most important is the section on component design. Your work from Step 1 above will go in that section. Most other sections can be done with much less detail than the component design section.

    Note:
    You may notice that several sections are similar to documents that you have 
    created previously, such as the Software Architecture Description and the 
    Software Requirements Specification. Feel free to copy and paste those 
    sections. The IEEE recommends that the SDD be as complete as possible, even 
    though this means duplicate content so that developers can get the 
    information they need without searching through too many separate documents.

##### Software Design Document (SDD) Template

1. ###### Title Page 
Name the project, list the team members, show the version number of the document, and include the phrase Software Design Description.

2. ###### Revisions
This page should contain a table similar to the one in the SRS that lists the date that a change was made to the document, a version number for each change, a description of the change, and the name of the author who made the change.

3. ###### Introduction
Describe the purpose of the document, the scope of the project, any other documents or sources that are referenced, and any special terms or acronyms that the project uses.

4. ###### System Overview
Give a general summary of the functionality of the system.

5. ###### System Architecture
This section contains the same content that is in your Software Architecture Description from the Week 3 Lab and is included here so the document stands on its own. It should contain a summary of the architectural design and its elements, whatever diagrams exist to communicate it (DFDs, hierarchy charts, block diagrams, UML, etc.), and your rationale for selecting the architecture.

6. ###### Data Dictionary
Create a list of names and brief definitions of the entities that your system will contain. In an object-oriented system, entities are usually classes, but they may also be nonclass elements such as primitive variables.

6. ###### Component Design
Describe what each component of the system will do and show static views, dynamic views, or both as appropriate. This is where you will put your design work from Step 1 above.

7. ###### Human Interface Design
This section describes how the system will interact with the user, including designs for the layout of screens and a description of how the interface will respond to user input or actions.

8. ###### Requirements Matrix
This matrix cross-references the requirements from your SRS with the components, interfaces, and other elements described above. This helps to ensure that we have covered all of the bases without doing anything extra that we did not need to do.

9. ###### Appendices
This optional section can be used to include any other information that might help developers understand the contents of this document.

### Step 3: Prepare for Construction
---
Because you will be working as a team to develop the software, it is important that you make some configuration management decisions before you begin coding. At a minimum, you will need to decide how the team will work together on writing the code. Most software engineers use some type of version control software. One option for this is [GitHub](https://github.com), which offers a limited version of the product for free. GitHub is a version control service that operates in a way that is typical of most version control tools, including keeping a modification history and providing the ability to revert to previous versions.

Student groups in the past have had reasonable success with cloud storage services such as [Google Drive](http://drive.google.com), which also offers free versions of their services. These options have the benefit of being extremely easy to set up and share with others, but they are not proper version control tools, so they must be used with extreme caution and diligence.

Investigate these options and discuss them with your team. Once you select one, have each of your team members set up an account and become acquainted with how to use it.

### Step 4: Construct the Architecture
---
The SRS and the SDD together are the guides to the construction effort. The SRS is the authority on the requirements, and the SDD describes how the system will be built to satisfy them. Now that you have both documents, you can begin construction.

Begin with the architecture. One sign of good architecture is that it allows incremental development from a skeletal framework. What this means is that you can begin writing your code by laying out the major elements with minimal or no functionality and then gradually build on the components one by one. Incomplete classes and empty functions are totally acceptable at this point, with the understanding that your team will complete them as construction activity moves forward.

You will have completed this step when the following two things happen.

1. All of the elements of your architecture are represented in the code as classes, functions, data structures, or whatever is appropriate for the element.
2. You can compile and run the program even though it may not do anything at this point.

### Step 5: Begin Constructing the Components
---
In CIS247, a prerequisite to this course, you learned how to read a class diagram and transform it into program code. This time, you'll be doing it from your own class diagrams. Building from the previous step and using your design as a blueprint, create the classes that will implement the functional requirements. You do not need to complete all of the code this week. It will be due with next week's lab, so you will have 2 weeks to finish coding the system.

The deliverable from this section will simply be a status description in Word on what program code is completed to date because you should have begun the coding this week. Please be very specific in your descriptions in terms of unit of code complete or percentage completed based on the total of program code or modules that need to be completed next week.

[Some videos linked here in DeVry internal]

### Step 6: Update Project Documents
---
Make whatever updates are necessary to the project plan, business problem scenario, or test plan. Also, complete your weekly time sheets.

### Step 7: Submit Deliverables
---
Create a zipped archive containing the following files.
1. Software design description (SDD) (completed template above)
2. Source code for architectural framework
3. Status and description of program code completed to date
4. Latest version of the project plan, business problem scenario, and test plan, if necessary
5. Individual team member cumulative time sheet (see the template in the Lab 1 assignment)

Submit the zipped file.

### Rubric
---
* Software Design Description: 35 points
* Architectural Framework Code: 20 points
* Status/Description of Program Code Completed to Date: 5 points
* Updated Project Documents and Time Sheets: 5 points
* Individual Team Member Cumulative Time Sheet (see the template link in Lab #1 assignment): 5 points
