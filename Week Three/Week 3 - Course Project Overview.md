## Course Project Lab 3 of 6: Software Architecture (70 points)

### Lab Overview
---
### Scenario/ Summary
---
As mentioned in this week's lesson, there are many activities that impact software quality, but none so much as the architecture. This week, you are going to explore the architectural considerations of the system that you are engineering and get some practice documenting your architectural decisions.

We do not have the opportunity to use the full ATAM that was mentioned in the lesson but this Course Project lab activity will give you a small taste of it.

### Deliverables
---
1. Updated SRS with Software System Attributes section completed (graded)
2. Select an architecture (graded)
3. Create a static view of the architecture (graded)
4. Create a dynamic view of the architecture (graded)
5. Create the software architecture description (graded)
6. Updated project documents (business problem scenario, project plan, test plan, etc.) (graded)

### Required Software
---
* Microsoft Word
    * Steps 1, 5, and 6
* Microsoft Visio (Available at: https://aka.ms/devtoolsforteaching. Be sure to log in with your DeVry credentials. Then click Software under Learning resources. In the search box, search for Visio.)
    * Steps 3 and 4
* Microsoft Project
    * Step 6

All software is available at [lab.devry](https://lab.devry.edu/)

### Lab Steps
---

### Step 1: Update the SRS With System Attributes
---
Because this is a Course Project, we do not have a previous project's architecture to use for creating a guidance model as we might in a real-world project. In the absence of such a model, the best way to begin is to look at some common architectural styles and decide which best fit our needs.

The main drivers for this decision are the nonfunctional requirements (NFR). The first step, then, is to decide on the most important qualities that our system must have. Discuss with your team and come to an agreement on which attributes matter most. Is the success of your system most affected by functionality, usability, reliability, performance, supportability, extensibility, modifiability, security, or something else? Once you have agreed on what is important, document this information in your SRS under Section 3.3 (Software System Attributes). Be sure to explain which qualities matter most, and why.

### Step 2: Select an Architecture
---
Next, you will need to choose some architectural styles that may support the qualities you identified in Step 1. There may be more than one style that applies to your situation, so you should consider the advantages and disadvantages of each. Furthermore, it is common for architectures to combine two or more styles to gain the benefits of each, and this is an option for you as well, though you will need to explain in detail how you plan to combine them.

To make the final decision regarding which architecture you choose, think about your quality attributes from the previous step and describe how you would design the system to support each of them. If that design conforms easily to the architecture, then you're probably on the right path. On the other hand, if you find that you cannot easily explain how the architecture supports the quality, then you may need to select a different architecture or customize the one you have chosen. For your convenience, here is a summary of common architectural styles as mentioned in the lesson; you are not necessarily limited to these.

* Data-centered architecture
* Data flow architecture
* Call-and-return architecture
* Tiered architecture
* Object-oriented architecture
* Layered architecture

### Step 3: Create a Static View of the Architecture
---
Now that you have selected an architecture and explained how it supports the NFRs, it is time to capture it in a diagram. Draw a diagram that shows the structure of the software in terms of its components and the connections between them. A UML component diagram is among the most common types of diagram for this purpose. UML class diagrams are effective as well. Any diagram that is accurate and understandable may be used, even if it is not UML.

### Step 4: Create a Dynamic View of the Architecure
---
As mentioned in the lesson, a good architecture is one that is well documented with at least one static and one dynamic view. To complete your architecture documentation, draw a diagram that shows how the components, processes, or other elements of the architecture communicate with each other. Common ways to represent this view are with UML sequence diagrams or activity diagrams. Flowcharts and data flow diagrams (DFDs) may be used as well. Again, the best choice is whatever most clearly and accurately shows the behavior of the architecture.

### Step 5: Create the Software Architecture Description
---
Your results from Steps 2, 3, and 4 will now be consolidated into a Software Architecture Description document. That document should contain the following information.

* A summary of the architectural style you chose in Step 2, along with an explanation of how it supports your quality attributes
* The static view from Step 3
* The dynamic view from Step 4

### Step 6: Update Project Documents
---
If your work on this lab activity required changes, additions, or clarifications to your project documents, then update them accordingly. Review these documents to make sure they are still accurate and consistent.

* Business Problem Scenario
* Project Plan
* Test Plan

### Step 7: Submit Deliverables
---
Create a zipped archive containing the following foles
1. Software Requirements Specification
2. Software Architecture Description (copy all diagrams into one Word document)
3. Latest version of the project plan, business problem scenario, and test plan

Submit the zipped file for grading.

### Rubric
---
* SRS with updated Section 2.3 (10 points)
* Justification for Architecture Decision (10 points)
* Static View (15 points)
* Dynamic View (15 points)
* Software Architecture Description (10 points)
* Updated Project Documents (10 points)