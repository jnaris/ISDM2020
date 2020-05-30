# Information System Development Methodologies - Assignment 1 Report
Authors: Leen Khawaja, Jasmin Narisetty, Yash Parge, Michael Zenkis

## 1. Objectives, Problem Definition
@Leen

## 2. Stakeholders
* Travel Company (client)
* Relationship Managers
* Customers
  * New customers
  * Existing/recurring customers

## 3. Design Thinking Approach
@Yash

## 4. Agile Methology Approach
The agile methodology that was decided upon for this project was Scrum. This methodology was chosen due to the project brief informing the team of the changing nature of the requirements of the project. The brief also mentions close contact with the stakeholders which will be delivering these updated and modified requirements throughout. Scrum allowed the team to effectively adjust and expect changes to occur throughout the development of the project and, throguh the scrum processes, the team was able to efficiently create the planning for the product to be implemented at a later stage. 

Following the scrum processes, the team worked effectively at self organising and ensuring that the work was completed according to the schedule of the various scrum members. The team adjusted meeting times according to various events  and committments team members had throughout the project, aligning with the flexibility attribute of scrum. 

Throughout the project, various team members were self allocating and discussing the various sections of work to be completed. Communication between team members was conducted through online Zoom meetings, which according to scrum and overarching agile, is most certainly not preferable. Due to the current situation the team members were in, we did not have the ability to meet face to face which would have been a more effective communication method. The team was able to adapt to the changing nature of work and focus on the high level of productivity characterised by scrum.

The high level of cooperation between team members was facilitated through the GitHub repository that was initiated at the beginning of the project. This repository was used in order to allow changes to be reviewed and discussed by the different members. Any concerns and changes were raised in the pull request thread, these changes were then made and the updates were added to the master repository branch.

The backlog which was created towards the beginning of the project outlines the user stories which are to be addressed during the implementation phase which falls outside of the scope of this project. However, due to the nature of this project, there were no official sprints used for implementation purposes. The team did participate in scrum meetings  whenever their was work being conducted on the project. This involved each team member discussing their current project on their task, outlining any problems they're facing as well as what they hope to achieve before the next meeting. These stand up scrum meetings only lasted for less than 10 minutes however gave all team members a clear idea of what others were working on as well as offer to help with any difficulties after the scrum meeting was over. 

The team worked effectively and employed many of the scrum processes and we aligned with the agile methodology in order 
to effectively deliver the planning and designing stage of the project. 

## 5. Assumptions
The team had discussions surrounding the scope of the system. We took into consideration the design of the solution that we would have to complete (such as Use cases, and class diagrams) as well as the specification and needs of the client. We wanted the solution to focus on **analysis** of data stored in the Profiler Tool, as well as the **process** of an RM receiving and conducting a sales call (before and during a call). We thought that data should come from a customer/RM database, the Profiler Tool should conduct the analysis of each customer/RM record, and the proposed system would match the customer and RM, based on their profile. So, the processes carried out within the proposed system must include the Profiler Tool and customer DB. 
Additionally, the team discussed whether or not actually handling calls (i.e., receiving a call from a customer or conducting a call) would be in scope. We thought this could be useful, however as the specification stated, a Call Management Centre (a different information system), would be handling this. This was helpful to us, as we could design the solution's focus to be on patterns analysis and providing suggestions to RMs to help improve customer service, rather than enabling the operations of the business. In sum, the solution is not business critical, meaning that the Travel Company does not require the system to receive and take calls. It is simply an additional service which helps **improve** RM accuracy, effectiveness, and customer satisfaction.

* The Profiler Tool will have the records of both Customers and RMs. This will be connected to the solution.
* All customer data (including repeat customer data) comes from the profiler tool. Therefore the customer score (1-10) is provided to the system via the profiler tool.
* The Target List will always match a Relationship Manager with their Specialised Package (the package that they are most familiar with, included in their Profile).
* In scope. The system will...
  * match the customer and RM (based on their profile).
  * create a target list for each RM (list of customers that the RM needs to contact).
  * generate a script for the RM to use in their call to the customer. The scripts will be pre-written and administered according to how well a customer’s profile suits the script. 
  * calculate the RM skill-score using data from the Profiler Tool and previous call history (stored on the system).
  * match customers to RMs based on skill-score and customer score.
* Out of scope. The system will not;
  * handle any data entry or storage during or after the sales process. For example, handle customer payment details or travel reservations.
  * store customer or RM *profiles*. It may retrieve the profiles from elsewhere (Profiler Tool) for analysis.
  * reroute or redirect inbound/outbound calls. This will be handled by the Call Management System.
  
## 6. Workproducts and Models
Requirements Backlog
ID | As a... | I want to... | So that I can... | Estimate (Fibonacci) | Priority (HML)
---|---------|--------------|------------------|----------------------|---------------
101|Relationship Manager|have customer calls relating to certain holiday packages routed to me|have full knowledge of the holiday package and satisfy the customer|21|H
102|Relationship Manager|have the system to automatically dial potential customers|spend more time on call selling packages|21|H
103|Relationship Manager|have the system to generate a script tailored to the customer profile|increase my performance and close sales|13|H
201|New Customer|Speak to an RM who understands my personality and needs|Purchase a travel package without any complications or misunderstanding|13|H
301|Recurring Customer|Be served quickly when I call the company|I do not have as long of a waiting time as newer customers|13|H
302|Recurring Customer|Talk to an RM who is aware of my travel history|I am not recommended the same travel packages again|8|M
302|Recurring Customer|Talk to an RM who is aware of my likes and dislikes|I am not recommended travel packages for places I will not enjoy|13|H

* Empathy Map
 * New Customer, Recurring Customer, Relationship Manager - See Commits
* Use Case Diagram
 * Outbound and Inbound - See Commits
* Class Diagram
 * See Commits
* Activity Diagram
 * Outbound and Inbound - See Commits
* Collaboration Diagram
 * See Commits
  
## 7. Competitive Advantages
Within the digital age, it is imperative that all industries and businesses take advantage of rapidly developing technologies to encourage change, improve existing processes, and potentially increase sales. Due to the advent of automation and networked technologies, manual labour has become expensive, inefficient, and time-consuming. Not only this, but storage and analysis of data becomes more difficult if a business is not able to implement technology solutions to accommodate the large volume of information which they are accumulating.

In the case of the Travel Company, the proposed solution aims to analyse customer and employee data, uncover otherwise unknown patterns, and make suggestions based on these patterns. These suggestions - such as customer/RM matching and generated sales scripts - can be utilised for the benefit of both the employee and customer, and this can lead to potential competitive advantages for the company. Should the design and implementation of the solution be successful and meet the quality of work expected by the client, the travel company may experience a **large increase in their capacity to receive and conduct customer calls, both inbound and outbound**. This increase means that RMs are spending more time conducting sales calls, potentially closing sales of travel packages, leading to an increase in sales and profit. Not only this, but the company gains a major competitive advantage due to the fact that they are implementing networked technologies that will enable analysis of data, matching RMs to customers based on preexisting data. Other companies in the market may not have thought of utilising existing stakeholder data in a way that improves customer satisfaction. As a result, **calls are more effective as time is not wasted offering products which customers are not interested in**, instead, an RM can utilise the proposed solution to quickly identify which products should be offered to the customer. This, in turn, **reduces the time taken to close a sale, providing more time for an RM to take additional sales calls**. Also, since the RM and customer are matched based on personality, and demographics, it is more likely that **a customer will develop a positive relationship with the RM based on common ground, encouraging repeat sales and recurring customers**. The generated script will also **streamline the RM’s work, and enable them to build and strengthen relationships with customers** as there is little guess-work involved in understanding a customer’s needs. Therefore, the successful implementation of the proposed information system will give the Travel Company a competitive advantage in relation to relationship marketing; by conducting more sales calls that are relevant and tailored to the individual customer, creating positive relationships and experiences to encourage repeat sales.

## 8. Effects of Project Failure
However, there are also some potential effects to the Travel Company should the project fail. Firstly, there are many reasons for project failure; not enough funds for resources, going over-budget, time constraints, complications regarding the client specification, executive decisions, and de-prioritisation due to the project being out of the scope of business critical activities. No matter how the project fails, there are always some adverse effects which can potentially leave a client financially damaged. For example, the Travel Company may not be able to handle the influx of calls which they are receiving at any given time, leading to **long waiting queues**. If a customer is not matched with an RM who understands their needs, **customers might become frustrated or angry with the RM’s inability to provide relevant products**, or the two parties may face **personality clashes** which can leave the customer feeling unsatisfied. This could result in poor customer experience and tarnished reputation via word-of-mouth marketing, triggering a loss of sales. Moreover, the RMs will not have the guidance and structure of a target list and generated scripts. This may lead to **inefficient sales calls** whereby the RM is not suited to discuss a certain product, and they might appear incompetent or unknowledgeable. 

## 9. Presentation
(link)
