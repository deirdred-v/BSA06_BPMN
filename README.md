# Modeling business processes

Summary:

Learning about the basic models and representations that develops during the analysis and design process. BPMN diagrams, their scope, and how to build them. And also compare it to the developed earlier 

## Contents

1. [Chapter I](#chapter-i) \
   1.1. [Task 1. Haircut Appointment](#41) \
   1.2. [Task 2. Delivery of Orders)](#42)
2. [Chapter II](#chapter-ii) \
   2.1. [Exercise 00 — Preparatory Work](#51) \
   2.2. [Exercise 01 — Identification of Main Business Processes](#52) \
   2.3. [Exercise 02 — Discussion of Business Processes](#53) \
   2.4. [Exercise 03 — Description of the Main Business Processes](#54) \
   2.5. [Exercise 04 — Development of Business Process Diagrams](#55) \
   2.6. [Exercise 05 — Revision of the Main Business Process Diagrams](#56)

## Chapter I <div id="chapter-i"></div>

### Description of tasks

### Task 1. Haircut Appointment <div id="41"></div>

The management of a chain of barbershops decided to implement an online booking system. The main objective is to develop the business by expanding the customer base through the possibility of online registration, as well as to reduce employee labour costs and manual labour by automatically informing customers through communication channels. 

Both registered and unregistered visitors can book an appointment on the website. When making an appointment, they can select the type of service: hairdressing or cosmetology, as well as the service itself, the master and the time from the available intervals. The system should provide automatic sending of reminders to clients through the communication channel chosen by the client (Telegram, WhatsApp, VK, SMS) according to the schedule set by the manager. After receiving a service, the system offers the client to evaluate the service and write suggestions on how to improve the work.

The schedule of masters and the services provided by each master should be entered by the manager, who may be more than one person. This person is also responsible for keeping the schedule up to date and adjusting it if necessary, communicating with customers manually, marking the service, charging and accepting payment, sending the payment data to the accounting department. The manager can also receive reports on completed services and view customer feedback.

Each master has the ability to view the schedule and appointments for their services, as well as customer reviews.

### Task 2. Delivery of Orders <div id="42"></div>

During the lockdown, many grocery stores and food companies dramatically increased their online sales and the need for quick delivery of small quantities to individual customers increased. 

A group of students got together and decided to create a delivery service startup. The idea is to quickly receive information about orders, pickup location and time, delivery location, desired delivery dates, and distribute this information to couriers who will pick up the order at the pickup location and deliver it to the delivery location. They decided to develop an online system where orders could be collected and quickly sorted for delivery by couriers.

The first step was to collect orders from stores and caterers in any way possible and have the operator enter them into the system in a consistent format, as well as developing a mobile application for the courier. The courier should be able to view order information, select an order from those available, book it, pick it up at the collection point and deliver it to the customer. The result of the courier's actions should be immediately reflected in the system via a mobile application. The system should also include a dispatcher who controls the couriers and reassigns orders if necessary. Information on received orders should be sent to the accounting department (to another IT system) to calculate delivery charges with order suppliers. Order delivery information should also be sent to the accounting department to calculate payment to couriers. Accrued payment should be transferred to the system and displayed in the courier's personal account. And there should also be an administrator's workstation, where couriers are registered and access rights are assigned to all of them.

## Chapter II <div id="chapter-ii"></div>

### Exercise 00 — Preparatory "Work" <div id="51"></div>

**For each task:**
Pick up the following artifacts from previous projects (chapter 1):

1. glossary;
2. onion diagram;
3. context diagram;
4. the problems to be solved by the system;
5. business requirements (business goals);
6. stakeholder roles;
7. role functions in the system;
8. data flows sent/received by external systems.

Indicate your answers in a file with corresponding names ex00\_<product prefix>\_<file name>.

### Exercise 01 — Identification of Main Business Processes <div id="52"></div>

**For task 1** identify main business processes. 

1. Identify business processes of level 1. Follow the decomposition rules. In case of violation, provide an explanation.
2. For each business process, select one person from your group and assign him/her to the role of business process owner. Determine who he/she is according to the role model of the task.
3. Make a list of the main business processes, specify:
   1. name (purpose) of the business process;
   2. business process identifier (alphanumeric, up to 5 characters); 
   3. business process result;
   4. owner (role in the task, last name, first name of the person assigned from the group).
4. Consider the criteria for identifying business processes:
   1. each business process must have a result;
   2. the results of business processes of the same level should be different.
5. Indicate your answers in the file ex01\_<product prefix>\_mpr.xlsx.

### Exercise 02 — Discussion of Business Processes <div id="53"></div>

**For task 1** have a discussion on each of the main business processes. 

1. Prepare questions for a business process discussion.
2. Consider both Exercise 03 of the current project and your own understanding of the business process when preparing questions.
3. Discuss the business process (it can be a role-playing game, brainstorming session, workshop — the team's choice).
4. Prepare a report of the discussion (discussed in detail in the BSA03 project), indicate:
   1. business process name;
   2. business process identifier;
   3. topic, purpose of the discussion;
   4. date of discussion, form of discussion, list of participants;
   5. facilitator, clerk, business process owner;
   6. issues discussed;
   7. answers to questions;
   8. on issues that caused controversial opinions: write down the opinions of the participants, the opinion of the business process owner, and the decision made.
5. Place the report in the file ex02\_<product prefix>\_<business process identifier>\_disc.docx. 

### Exercise 03 — Description of the Main Business Processes <div id="54"></div>

**For task 1** describe each of the main business processes, write them in a single table. 

1. Specify for each main business process:
   1. business process name;
   2. business process identifier;
   3. Start (input): 
      1. initiating event;
      2. resources to create a product (result);
   4. end (exit): 
      1. resulting event; 
      2. the finished product/result of a business process;
   5. owner:
      1. role;
      2. surname, first name of the assigned member of the group; 
   6. list of business process executors (roles in the task);
   7. used resources (information data used in the business process);
   8. relationships with other main business processes.
2. Indicate your answers in the file ex03\_<product prefix>\_mpr.xlsx.

### Exercise 04 — Development of Business Process Diagrams <div id="55"></div>

**For task 1** create a process diagram of each main business process in BPMN notation.

1. Specify the name of the business process and its identifier in the diagram.
2. Specify the owner of the business process (who is responsible for execution) next to the name.
3. Specify the initial event, what the event is about, who the event comes from (executor or automatically).
4. Specify the input of the business process: the resources required to create the result of the business process (information, personnel) from which the result is obtained.
5. Specify process steps, branches, data and relationships.
6. Specify intermediate events if necessary.
7. Apply lanes/pools or specify executors on footnotes (artifacts) if necessary. 
8. Specify the end event and result of the business process.
9. Indicate your answers in the file ex04\_<product prefix>\_bpmn\_N.xxx (xxx is an extension, N — business process identifier).

### Exercise 05 — Revision of the Main Business Process Diagrams <div id="56"></div>

**For task 1** check the consistency of the main business process diagrams and other task artifacts.

1. Check the consistency of the stakeholders and the roles in:
   1. context diagram;
   2. onion diagram;
   3. stakeholders list;
   4. main business process diagrams.
2. Check that the glossary contains the domain concepts specified in the main business process diagrams.
3. Check that the problems for which the system is being created can be solved in the execution of the main business processes.
4. Check that the business requirements of the system can be achieved by the main business processes.
5. Check that the main business processes ensure that the functions of the system roles are fulfilled. 
6. Place the results in the "Artifact Comparison" table (https://docs.google.com/spreadsheets/d/1tKYX2C6t6lXdRNa14qHG4j2gKa\_mQSW5/edit#gid=2122219759).
7. In case of inconsistency:
   1. report the inconsistency for each case in a table;
   2. indicate the need (or lack of need) to modify the artifacts under consideration;
   3. correct an artifact that requires clarification.
8. Indicate your answers in the file ex05\_<product prefix>\_rev.xlsx.
9. Place a new revision of the refined artifact with a ex05 prefix in the name.
