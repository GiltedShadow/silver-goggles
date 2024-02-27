## Equipment Checkout System (ECS) Case Study (Business Problem Scenario)

### Introduction
---
In this section, you will learn the background information that will prepare you to understand and complete each of the Course Project Lab assignments of this case study. This information includes the business background, the problem description, and the descriptions of the problems that triggered the need for the system project.

You will use this case study Business Problem Scenario information in each of the six Course Project Lab assignments at different levels of detail as you progress through the software development life cycle (SDLC), but the core deliverables will be in the last four lab assignments. Keep in mind, the deliverables to be created in the first two lab assignments are from the core skills you obtained in the Software Engineering Part 1 course.

Also keep in mind, based on all of the information below, you will be able to complete the Business Problem Scenario template as part of the Course Project Lab 1 deliverables.

### Background and Problem
---
#### Background

GB Manufacturing is a producer of electronic components and testing equipment. The company is located in the New York City area with multiple plants. The corporation has over 10,000 full-time employees.

Approximately 200 employees are employed with the company's maintenance department, which is responsible for the maintenance of the building and grounds. Maintenance has assigned a group of employees to provide maintenance for each building or plant. The employees assigned to each building or plant collectively possess the skills needed to provide proper upkeep. Such employees include carpenters, electricians, painters, welders, plumbers, and the like. The maintenance department also has a group of employees with special skills to assist with special projects that may arise.

#### Problem

In August of 2014, Bill Venkman and his management staff completed a 1-week retreat aimed at assessing the maintenance operations. Several initiatives resulted from this retreat. It was determined that the most important initiatives were those that primarily dealt with the equipment depot operation.

The equipment depot's function is to provide the equipment needed by maintenance employees to perform their job duties. Employees are provided with a toolbox containing commonly used and relatively inexpensive tools, such as hammers, screwdrivers, tape measures, and so on. Other tools and pieces of equipment that are needed to complete a job must be checked out through the equipment depot. When the job is completed, the employee must return the checked-out equipment.

Often, pieces of equipment become lost, stolen, or damaged and are therefore never checked back in and made available for others. The dollar amount of lost and stolen equipment has reached an alarming total. It has been estimated that more than $50,000 worth of tools are lost or stolen each year. Bill Venkman has decided that something must be done to get the losses under control. Thus, he is giving top priority to the development of a new, automated equipment checkout system that will track the check-in and check-out of equipment.

The materials warehouse is responsible for obtaining and storing supplies that are needed to complete jobs. For example, the materials warehouse makes sure to maintain a supply of screws, nails, plywood, drywall, and other materials. The materials warehouse operates in two locations. The main materials warehouse is a large building located approximately 1 mi away from the main campus. For convenience, a smaller materials warehouse is located near the central office and stores a small amount of the most commonly used materials. When workers need materials for a job assignment, they are supposed to check both warehouses to see if the goods are available. Unfortunately, the employees are often impatient and will simply check the availability of materials at the smaller, more conveniently located warehouse. If the goods are not available, they routinely choose to simply move on to the next job assignment rather than checking with the main warehouse. Though the main warehouse will deliver the materials, employees prefer not to have to wait for delivery. To complicate things further, even though the materials may be available at the larger warehouse, employees frequently request that the smaller warehouse order needed materials that are not in stock there. The net result is excessive inventory and inventory carrying costs!

Although management is not sure of the total dollar amount that can be attributed to carrying excessive inventory, they are in agreement that it is likely very substantial; therefore, a new and improved warehousing system is another top priority for the maintenance department.

### System Request Information and Problem Matrix
---
#### PROBLEMS, OPPORTUNITIES, OBJECTIVES, AND CONSTRAINTS MATRIX
| __Project:__ Equipment Checkout System | __Project Manager:__ (instructor name) | 
| --- | --- |
| __Created vy:__ (student name) | __Last Updated by:__ (student name) |
| __Date Created:__ 2/27/24 | __Date Last Updated:__ 2/27/24 |


  
<table>
  <tr>
    <th align="left" colspan="2"> CAUSE AND EFFECT ANALYSIS </th>
    <th align="left"> SYSTEM IMPROVEMENT OBJECTIVES </th>
  </tr>
  <tr>
    <th align="left"> Problem or Opportunity </th>
    <th align="left"> Causes and Effects </th>
    <th align="left"> System Objectives </th>
  <tr>
    <td rowspan="7"> 1. It takes too long to process a single equipment checkout </td>
    <th align="left"> Cause(s): </th>
    <td rowspan="7"> 1. Reduce the amount of time it takes to process a single equipment checkout to less than 2 minutes </td>
  </tr>
  <tr>
    <td> 1 Employee and equipment records are maintained manually and are tedious to locate. </td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <th align="left"> Effect(s): </th>
  </tr>
  <tr>
    <td> 1. It takes 2 to 10 minutes to process a single equipment checkout. </td>
  </tr>
  <tr>
    <td> 2. There are lines of employees having to wait to check in and out tools at the end and beginning of each shift. </td>
  </tr>
  <tr>
    <td> 3. Employee resentment toward Equipment Depot is growing. </td>
  </tr>
  <tr>
    <td rowspan="5"> 2. It takes too long to process an employee termination </td>
    <th align="left"> Cause(s): </th>
    <td rowspan="5"> 1. Reduce the amount of time it takes to process an employee termination to less than 2 minutes </td>
  </tr>
  <tr>
    <td> 1. Employee records are manually stored and difficult to retrieve for a particular employee. </td>
  </tr>
  <tr>
    <td> 2. Supervisors do not promptly and reliably return the equipment of a terminated employee </td>
  </tr>
  <tr>
    <th align="left"> Effect(s): </th>
  </tr>
  <tr>
    <td> 1. It takes 10 minutes to process an employee termination. </td>
  </tr>
  <tr>
    <td rowspan="4"> 3. Often equipment that is lost and then subsequently returned cannot be matched with the employee who checked it out </td>
    <th align="left"> Cause(s): </th>
    <td rowspan="4"> 1. In less than 30 seconds, locate the employee to whom returned equipment belonged </td>
  </tr>
  <tr>
    <td> 1. The staff member must manually go through each check-in and checkout form to match the tool with the employee </td>
  </tr>
  <tr>
    <th align="left"> Effect(s): </th>
  </tr>
  <tr>
    <td> 1. This tedious process results in significant lost time. </td>
  </tr>
  <tr>
    <td rowspan="2"> 4. There is an opportunity to increase safety by enforcing requirements that employees must have the correct skill classification for the equipment they are checking out </td>
    <th align="left"> Effect(s): </th>
    <td rowspan="2"> 1. The system will allow equipment to be checked out only by employees with the correct skill classification </td>
  </tr>
  <tr>
    <td> 1. Enforcing these requirements could decrease lost work time due to accidents, decrease damage to equipment, and possibly decrease liability</td>
  </tr>
  <tr>
    <td rowspan="4"> 5. When equipment is ordered, the Equipment Depot staff often fields several calls concerning the status of the order. When the order comes in, they have to notify the employee who wanted the equipment </td>
    <th align="left"> Cause(s): </th>
    <td rowspan="4"> 1. The system will automate this process </td>
  </tr>
  <tr>
    <td> 1. The manual log that is currently kept of orders is difficult to work with. </td>
  </tr>
  <tr>
    <th align="left"> Effect(s): </th>
  </tr>
  <tr>
    <td> 1. This manual system results in significant lost time </td>
  </tr>
  <tr>
    <td rowspan="4"> 6. Inability to generate reports to support their decision-making needs. </td>
    <th align="left"> Cause(s): </th>
    <td> 1. Provide easily accessible records </td>
  </tr>
  <tr>
    <td> 1. Most records are manually kept and are too tedious to use. </td>
    <td> 2. Provide staff with the ability to obtain immediate access to predefined reports. </td>
  </tr>
  <tr>
    <th align="left"> Effect(s): </th>
    <td rowspan="2"> 3. Provide staff with the ability to easily define new reports at a decision-making time of need </td>
  </tr>
  <tr>
    <td> 1. Needed reports are not generated. </td>
  </tr>
  <tr>
    <td rowspan="4"> 7. Employees don't have what equipment they have in their possession. </td>
    <th align="left"> Causes(s): </th>
    <td rowspan="2"> 1. Provide an easily accessible record storage system. </td>
  </tr>
  <tr>
    <td> 1. Manual records of employees and equipment transactions are too tedious to reference. </td>
  </tr>
  <tr>
    <th align="left"> Effect(s): </th>
    <td rowspan="2"> 2. Provide each employee with a periodic statement of their equipment transactions. </td>
  </tr>
  <tr>
    <td> 1. Employees are not informed of equipment possessions and therefore are not held accountable. </td>
  </tr>
  <tr>
    <td rowspan="4"> 8. The Equipment Depot is not able to identify employees that have excessive equipment losses. </td>
    <th align="left"> Causes(s): </th>
    <td rowspan="2"> 1. Provide the ability to conduct an employee tool check-in/out analysis. </td>
  </tr>
  <tr>
    <td> 1. Manual records of employees and equipment transactions are too tedious to reference. </td>
  </tr>
  <tr>
    <th align="left"> Effect(s): </th>
    <td rowspan="2"> 2. Generate an exception report that identifies problem situations and employees. </td>
  </tr>
  <tr>
    <td> 1. The Equipment Depot staff cannot follow up on problem employees and equipment checkouts. </td>
  </tr>
</table>

#### Lab assignment titles
* Project Scope and High-Level Requirements
* Requirements and UML-OOAD Diagrams
* Software Architechture
* Software Design and Construction
* Construction and Testing
* Testing and Maintenance

### Course Project Lab Deliverables Summary
---
Again, you will use this case study Business Problem Scenario information in each of the six Course Project Lab assignments at different levels of detail as you progress through the SDLC, but the core deliverables will be in the last four lab assignments. Keep in mind, deliverables created in the first two lab assignments are from the core skills you obtained in the Software Engineering Part 1 course. 

In Week 4, there is no lab assignment, but the Midterm is due. Please take advantage of Week 4 to get a jump-start on your Week 5 Course Project Lab 4 assignment.

Please see the weekly Course Project Lab assignment pages for detailed deliverables and instructions.

<table>
  <tr>
    <th align="left"> Category </th>
    <th align="left"> Points </th>
    <th align="left"> % </th>
    <th align="left"> Description </th>
  </tr>
  <tr>
    <td> WK 1 -- Course Project Lab 1 </td>
    <td> 80 </td>
    <td> 13.95% </td>
    <td> Project Scope and High-Level Requirements </td>
  </tr>
  <tr>
    <td> WK2 -- Course Project Lab 2 </td>
    <td> 80 </td>
    <td> 13.95% </td>
    <td> Requirements and UML-OOAD Diagrams </td>
  </tr>
  <tr>
    <td> WK 3 -- Course Project Lab 3 </td>
    <td> 80 </td>
    <td> 16.28% </td>
    <td> Software Architecture </td>
  </tr>
  <tr>
    <td> WK 4 -- No Lab Assignments </td>
    <td> N/A </td>
    <td> N/A </td>
    <td> N/A </td>
  </tr>
  <tr>
    <td> WK 5 -- Course Project Lab 4 </td>
    <td> 80 </td>
    <td> 16.28% </td>
    <td> Software Design and Construction </td>
  </tr>
  <tr>
    <td> WK 6 -- Course Project Lab 5 </td>
    <td> 80 </td>
    <td> 16.28% </td>
    <td> Construction and Testing </td>
  </tr>
  <tr>
    <td> WK 7 -- Course Project Lab 6 </td>
    <td> 160 </td>
    <td> 23.26% </td>
    <td> Testing and Maintenance </td>
  </tr>
  <tr>
    <th align="left"> Total </th>
    <th align="left"> 560 </th>
    <th align="left"> 100% </th>
    <th align="left"> </th>
  </tr>
</table>

### Course Project Grading Rubric
---

<table>
  <tr>
    <th align="left"> Category </th>
    <th align="left"> Points </th>
    <th align="left"> % </th>
    <th align="left"> Criteria </th>
  </tr>
  <tr>
    <td> Code </td>
    <td> 200 </td>
    <td> 36% </td>
    <td> The code is well written including comments. Several test cases showing the code working with multiple inputs are illustrated. Accuracy of the code and readability adhering to good programming principles are required.

 </td>
  </tr>
  <tr>
    <td> Planning and Design </td>
    <td> 225 </td>
    <td> 40% </td>
    <td> The diagrams and planning documents are clear, concise, and fully describe the problem. The diagrams and planning documents are consistent with the implementation.

 </td>
  </tr>
  <tr>
    <td> Organization and Cohesiveness </td>
    <td> 45 </td>
    <td> 8% </td>
    <td> The major points are clearly stated, well supported by specific details (examples or analysis), and are organized logically. It links theory to relevant examples of current experience and industry practice with depth and clarity. Content is accurate and information is presented in a logical order. It flows well and logically, reflecting adequate research to identify the components necessary to meet the objectives.

 </td>
  </tr>
  <tr>
    <td> Documentation and Formatting </td>
    <td> 45 </td>
    <td> 8% </td>
    <td> It uses appropriate industry vocabulary, concepts, and theories. Paragraph transitions facilitate logical flow. Transitions are smooth, interesting, and the layout and formatting helps the reader process the information.

 </td>
  </tr>
  <tr>
    <td> Editing </td>
    <td> 45 </td>
    <td> 7% </td>
    <td> Proper grammar is expected. Quality work will be free of any spelling, punctuation, or grammatical errors. Sentences and paragraphs will be clear, concise, and factually correct.

 </td>
  </tr>
  <tr>
    <th align="left"> Total </th>
    <th align="left"> 560 </th>
    <th align="left"> 100% </th>
    <th align="left"> A quality assignment to reach or exceed all of the above requirements </th>
  </tr>
</table>
