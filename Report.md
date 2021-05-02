# Stakeholders

| Name | Categories | Role | Impact |
| ---- | ---------- | ---- | ------ |
| General Public (Patients) | Uses/Affected with | <ul><li>Register to the system</li><li>Booked COVID-19 vaccine jab</li><li>Getting COVID-19 vaccine on vaccination centre</li></ul> | Increase the percentage of people vaccinated  |
| Federal Health Authorities | Uses/Affected with | Responsible for monitoring COVID-19 vaccine stocks | COVID-19 vaccine stock running effectively |
| Health Department Minister | Uses/Affected with | <ul><li>Prepare & responsible for COVID-19 vaccine distribution</li><li>Plan vaccine program based on priority occupations</li></ul>  | <ul><li>Smooth & Efficient rollout program</li><li>Successfully distributing COVID-19 vaccine</li><li>Decrease COVID-19 cases</li></ul> |
| Chief Information Technology Officer (CTO) | Uses/Affected with | Recruit a team to design the system | Smooth & Efficient rollout program |
| System Developers | Affected with | Build & design Vaccine Management System (VMS) | Fullfilling business requirements |
| Healthcare Workers <ul><li>Doctors</li><li>Nurses</li><li>Paramedic Staffs</li></ul> | Uses/Affected with | <ul><li>Vaccine Administrators</li><li>Ensure no vaccine is wasted</li><li>Inject patients with COVID-19 vaccine</li></ul> | Decrease the workhours |

# Design Thinking
The Design Thinking Methodology refers to a non-linear iterative process that teams use to understand the users, challenge the assumptions, redefine the problems, and thus, create innovative solutions that hopes to make significant improvement to individuals in society. Each phase of design thinking will be analysed closely in order to provide a better understanding on how each phase play a major role in reducing and resolving issues related to developing the Vaccine Management System (VMS). Below is a breakdown of the five phases in design thinking and how the team plans to approach building this solution: 

## 1. Empathise 
Empathising is the first step of the Design Thinking and allows for the understanding of the user’s pain points and potential improvements that will need to be developed to enhance the user experience. In order to enhance the user experience, it is important to understand the user, how they feel, and how this system will affect their way of functioning in society. A method to approach this phase requires a need to interact with the users and taking into account their viewpoint on the issue. By viewing the character profile for each of the stakeholders involved, an empathy map was created to provide a visualisation on the user’s attitude and behaviour found below. This will assist the UX Team in revealing any the current user data to support a greater understanding of end users.

### General Public (Patient)
#### Point of View (POV) Statement
Patients (member of public) who are interested in getting vaccinated need to know whether they need to get vaccinated or not, as there is a lot of misleading information that is being shared and doesn't have any information to book for one.

#### Empathy Maps
![alt text](https://github.com/bryancolin/ISDM-Group-1/blob/week-1/Images/Empathy%20Maps/Empathy%20Map%20for%20General%20Public.png)

#### Assumptions
- Patients have not received any COVID-19 vaccine yet either 
- Patients will receive two doses of COVID-19 vaccine which means they will have to come back after the first vaccination within the set period of time
- Patients have no knowledge or anything regarding how to get vaccinated

### Healthcare Workers 
#### Point of View (POV) Statement
The Healthcare workers need to be treated with the vaccine themselves before assisting patients with their treatment as this will ensure they do not spread the virus any further to provide their assistance.

#### Empathy Maps
![alt text](https://github.com/bryancolin/ISDM-Group-1/blob/week-1/Images/Empathy%20Maps/Empathy%20Map%20for%20Healthcare%20Workers.png)

#### Assumptions
- Healthcare workers have already been vaccinated before treating others
- Healthcare workers have an understanding of the vaccination procedure

### Chief Technical Officers 
#### Point of View (POV) Statement
The CTO, directed by the Health Minister, needs to ensure that the team develops the system to be able to effectively support the vaccination rollout because it must be successul in order to accurately communicate vaccination information. This includes to both the end-users, being the public/patients, and those who will be affected by the system, being the healthcare workers.

#### Empathy Maps
![alt text](https://github.com/bryancolin/ISDM-Group-1/blob/e9b1996583414dfff81bd23078974a9970d896bf/Images/Empathy%20Maps/Empathy%20Map%20for%20CTO%20&%20System%20Developers.png) 

#### Assumptions
- The CTO is heavily invested in the development of the VMS, interacting heavily with the system development team to ensure the system communicates the goals set by the Health Minister.

## 2. Define 
After gathering user information and relevant data, it opens up a better exploration and understanding into the core problems identified by users. 

### Problem Definition

The state of Health Department Minister who is responsible for COVID-19 vaccination rollout program is having issues in distributing the COVID-19 vaccine to the public.

### Project Objectives

The goal of this project is to develop and design vaccination management system (VMS). The system will allow public to book for COVID-19 vaccine jab through a platform & provide the details of the vaccination centre. 

## 3. Ideate 
The ideation stage is essential to the creative development of design thinking. By utilising ideation techniques, it will allow for the expansion of the problem space and the motivation of free thinking. Through understanding of potential user pains and gains, the development team are able to look for alternative ways in viewing the problem. With the empathy map developed during the “Empathise Phase” of the design thinking process, illustrates the stakeholder’s emotions and background on the problem. 

From the empathy maps, the stakeholder’s point of view can allow for setting the foundations of the idea stage by developing “How Might We (“HMW”) Statements to launch brainstorming of other ideation sessions of the team. Below are some of the HMW statements that will trigger the development team’s ideas on how they can effectively create an end solution to the users. 

### How Might We (HMW) Statement

#### General Public
- How Might We share the information details of COVID-19 vaccine for public member to view?
- How Might We ensure that COVID-19 vaccine is safe to have to the general public?
- How Might We encourage member of public to have COVID-19 vaccine?
- How Might We provide member of public to easily register on our system for COVID-19 vaccine ticket?
- How Might We facilitate vaccination centre to the public?
- How Might We contact the public who has successfully book for COVID-19 vaccine?
- How Might We make sure that the public are eligible to have COVID-19 vaccine before registration?
- How Might We contact the public to come and receive second vaccination after the first one?
- How Might We label them as vaccinated people after they have two doses of COVID-19 vaccine? Certificate?

#### Healthcare Workers
- How Might We spread the word about the COVID-19 Vaccine?
- How Might We persuade the general public to take the vaccine?
- How Might We organize a faster rollout system?
- How Might We facilitate the demand for the vaccine?
- How Might We inform who is next in line for their vaccinations?

#### Chief Technical Officer
- How Might We encourage effective communication and coordination between the CTO and the system developers?
- How Might We effectively incorporate the goals set by the CTO into  development of the system?
- How Might We ensure the CTO communicates the goals set by the health minister to the development team?
- How Might We ensure that the system runs smoothly and accurently conveys the vaccine information so to avoid confusion with the patients and healthcare workers?
- How Might We request feedback from the health minister at various stages of the system development stage to ensure it meets requirements?

### Requirements

#### Functional Requirements
- The system shall allow general public to register to the system
- The system shall allow general public to sign in to the system
- The system shall allow general public to view their ticket details 
- The system shall allow general public to be matched with the closest vaccination centre
- The system shall allow general public to view their account personal details
- The system shall allow general public to be able to receive notification for 1st/2nd vaccine
- The system shall allow general public to view vaccination certificate
- The system shall allow general public to download vaccination certificate
- The system shall allow general public to view additional info of COVID-19 vaccine
- The system shall allow general public to sign out from the system  
- The system shall allow healthcare workers to view shipment details for the vaccine
- The system shall allow healthcare workers to view the dosage count for each type of vaccine
- The system shall allow healthcare workers to update the dosage count for each type of vaccine
- The system shall allow healthcare workers to view instructions on vaccine administration protocol 
- The system shall allow healthcare workers to download intructions on vaccine administration protocol 
- The system shall allow healthcare workers to view applications including date and time for each patient assigned
- The system shall allow healthcare workers to record when a dose and given and update the dosage count
- The system shall allow healthcare workers to notify patient for their second dosage
- The system shall allow federal health authorities to set up rollout plan based on priority occupations
- The system shall allow federal health authorities to register vaccination centre location to the system

#### Non-Functional Requirements
- The system should be able operational 24 hours a day and 7 days a week
- The system should run without crashing/stalling
- The system should achieve a 99.87% success rate
- Passwords should be strong, and unseen when sign in
- The system shall provide 100% access reliability
- The system shall support multiple languages such as English and Chinese

### User Stories (Prioritised)

| User Story | Activity | As a/an | I want to | So that | Pritority | 
| ------------- | -------- | ------- | --------- | ------- | ---------------- | 
| 001 | Register | Patient | register online with all the required details (address, medicare number, personal details) | I can receive a ticket and receive the COVID-19 vaccine | High | 
| 002 | Sign In | Patient | login to the vaccine management system (VSM) | I can view account & ticket details | High | 
| 003 | Notications for 1st/2nd vaccine | Patient | be able to receive a notification/alert for the second vaccination process | I can complete the vaccination process  | High | 
| 004 | Download Vaccination Certificate | Patient | be able to view & download the certificate once the vaccination process has been completed | I have evidence of receiving the vaccination & be able to travel soon | High | 
| 005 | View additional info of COVID-19 vaccine | Patient | be able to see any important information/resources associated with the vaccine | I am more confindent in receiving the COVID-19 vaccine | Medium | 
| 006 | Receive and record vaccine amount from shipments | Healthcare worker | retrieve the vaccine from the shipments and record the dosage numbers | the COVID-19 vaccine count can be recorded | High | 
| 007 | View application forms and timings | Healthcare worker | check which applicant is coming to receive their vaccine and at what time | I can keep track of who is going to receive the COVID-19 vaccine | High | 
| 008 | View instructions and conditions needed for vaccine administration | Healthcare worker | check a manual for administration either via a manual booklet or an online document | I can know how to properly administer the vaccine  | Medium | 
| 009 | Update the system when a dose is given | Healthcare worker | administer the dosage of the vaccine to the patient and record the dose given | the patient can complete their first dose of the COVID-19 vaccine | High | 
| 010 | Notify patient if another dosage is needed on a later date | Healthcare worker | organize the date and time for the second dose if needed | the patient can be fully vaccinated or so the patient can come back for their second dosage if needed | High | 
| 011 | Setup vaccination centre location | Federal Health Authority | register the location of vaccination centres in the system | the system can match the booked patient with the closest centre | High |

## 4. Prototype
The system developers/design will then produce a few inexpensive, scaled-down versions of the application with detailed features found within it. The prototype will continually be tested by health officers including the nurses and doctors, and the testing team that is under the CTO to identify whether the system achieves the best possible solution for the issues acknowledged in the first three stages above. The solution is to create a system that allows the user to view any vaccination points according to the administrating capacity which will be executed within the prototype. Additionally, class diagrams are also designed to better understand the flow and function of the application.

### Use Case Diagram
![Alt Text](https://github.com/bryancolin/ISDM-Group-1/blob/week-3/Images/Diagrams/Use%20Case%20Diagram.jpg)

### Activity Diagrams

#### General Public (Patient)

##### Get Ticket
![ALT Text](https://github.com/bryancolin/ISDM-Group-1/blob/week-3/Images/Diagrams/Activity%20Diagram%20(Patient)%20-%20Get%20Ticket.jpg)

##### View Vaccination Certificate
![Alt Text](https://github.com/bryancolin/ISDM-Group-1/blob/week-3/Images/Diagrams/Activity%20Diagram%20(Patient)%20-%20View%20Vaccination%20Certificate.jpg)

#### Healthcare Worker

##### View Application Form & Record
![ALT Text](https://github.com/bryancolin/ISDM-Group-1/blob/week-3/Images/Diagrams/Activity%20Diagram%20(Healthcare%20Worker)%20-%20View%20Application%20Form%20%26%20Record.jpg)

### Class Diagram
![ALT Text](https://github.com/bryancolin/ISDM-Group-1/blob/week-3/Images/Diagrams/Class%20Diagram.jpg)

### Collaborative Diagrams

#### General Public (Patient)

##### Get Ticket 
![ALT Text](https://github.com/bryancolin/ISDM-Group-1/blob/week-3/Images/Diagrams/Collaboration%20Diagram%20(Patient)%20-%20Get%20Ticket.jpg)

##### View Vacinnation Certificate
![ALT Text](https://github.com/bryancolin/ISDM-Group-1/blob/week-3/Images/Diagrams/Collaboration%20Diagram%20(Patient)%20-%20Get%20Downloadable%20Certificate.jpg)

#### Healthcare Worker

##### View Application Form & Record
![ALT Text](https://github.com/bryancolin/ISDM-Group-1/blob/week-3/Images/Diagrams/Collaboration%20Diagram%20(Healthcare%20Worker)%20-%20Record%20Vaccinated%20People.jpg)


## 5. Test 
In the testing phase, the system tests along with the potential future users of the application will experiment with the prototype developed. The results outputted during this process will allow the development team to redefine any issues needed and enable a full understanding of the user experience along with their conditions of use.

# Agile Methodology
The Agile Methodology has been chosen for the VMS Project as it provides a versatile structure for developing an effective solution that focus on the customers. The Scrum Framework in particular, is centred around continuous learning and adjustment to fluctuating factors. It acknowledges the fact that the team doesn't know everything at the start of the project and will evolve through experience. This means that the team can adapt to changing conditions and re-prioritisation built within the process through the short release cycles ultimately enabling them to constantly learn and improve. This in turn will save large amounts of time, cost, and resources given to the project. 

![differences-lean-agile-scrum-scrum-process](https://user-images.githubusercontent.com/48747159/116772861-1f7bfb00-aa95-11eb-9178-90372f7df6f7.jpeg)

## Preparation
The first stage of Scrum in the Agile Methodology is setting up the project foundations. These includes the sprint planning, putting together the sprint backlog, and deciding on the scrum roles. 

The scrum roles have been divided accordingly into different roles including the Project Owner, Scrum Master, and Development Team. The roles were distributed based on the individual's skills and experience to ensure that the work produced is at a high quality. The team took the initiative to be self-organising and adapt to each other to allow for the best outcomes. Furthermore, they will be cross-functional to ensure that each member can work independently in successfully achieving the outcomes. The roles are as follows: 

* Product Owner: Chief Technology Officer (CTO)
* Scrum Master: Bryan Colin
* Development Team: Adam Airey, Pornmonireachsak Aun, Dylan Cai, Kunyang Dai, and Jasmina Dang

## Product Backlog 
The Project Owner is responsible for the product backlog and has a say in prioritising the user stories, requirements and changes. The Product backlog will contain all necessary requirements to effectively create the VMS and is thus presented at an ordered list. It is important for the Agile Backlog to be well-prioritised as it not only makes the release and iteration planning easier, it demonstrates all the aspects the team intends to spent time on including the work the customer do not see. The user stories will be used for the product backlog as it breaks down the user needs and requirements which ultimately allow the team to create a roadmap for building the system. The backlog will be prioritised based on the importance in each sprint. 

## Sprint Planning Meeting
Sprint Planning is an event in Scrum that kicks off the beginning of the sprint. This event is to define what can be delivered in the sprint and how the work can be achieved. Sprint is a set period of time where all the work is done and is done in collaboration with the whole scrum team. The planning meeting will involve the scrum master, project owner, and development team who will decide how the produce will proceed and a plan will then be developed for their own use.It is also this meeting where the team discusses "The Definition of Done" on each of the user stories to ensure that the work is completed in a timely manner. The team defines The Definition of Done when: 

* All Prototypes & Models have been completed to its best abilities
* UML diagrams have been reviewed by two member in the development team as well as the project owner & product owner
* Feedback has been provided to the author of the diagrams 

The backlog is accessed in this meeting and will have user stories split up into sprint as shown in the table below:

| Sprint | Duration | User Story ID | Goal |
| ------ | -------- | ------------- | ---- |
| 1 | 2 | 001, 002, 005, 006, 007, 008 | To set up VMS allowing users to register and login in order to achieve the expectations of the owner and the manager | 
| 2 | 2 | 003, 004, 009, 010, 011 | To create a notification and mapping vaccine system to make the Vaccination Process more efficient | 

[//]: <img width="735" alt="Screen Shot 2021-05-01 at 4 16 10 pm" src="https://user-images.githubusercontent.com/48747159/116773402-8ea71e80-aa98-11eb-9507-f4d7bf709f92.png"> (This is also a comment.)

## Daily Scrum Meeting 
Also known as daily stand-ups, the daily scrum meetings are a great way for the team to understand each other's progress as well as help flag any team blockers. It also strengthens the team when everyone shares the progress that they are contributing. The regular intervals or these meetings also keeps everyone excited about the team's overall contribution to the organisation, thus leading to ultimately transparency found throughout the team. Every member answers these three questions to generate structure to the meetings as they should only be 5 minutes long: 

* What did I work on yesterday?
* What did I work on today?
* What issues are blocking me?

Any blockers that were brought up during these meetings were openly discussed within the team and management to derive a solution where each meeting had a limit of 5-10 minutes max.

## Sprint Review 
The execution of all the two sprints were successful as a result of the effective implementation of the Agile Methodology (in particular Scrum) which allowed for the incremental succession of tasks being completed as well as enabling effective communication between the development team and management. From the sprint planning, all the way to the daily scrum meeting, the team was able to complete their tasks within a timely manner through having a sprint review. Although the system is not ready for deployment nor for sale, the working model has been developed and reviewed by the product owner. Some of the work showcased include the UML diagrams, Project Objectives and a low fidelity prototype of the system. A sprint review is a celebration of completing the tasks on time based on what the team defines 'The definition of done' on each of the work items and was done at the end of Sprint 1 and 2. 

## Sprint Retrospective 
The sprint retrospective is when the team reflects on the past in order to improve in the future. In this case, a retrospective was done after Sprint 1 as it gave the team a chance to reflect on their work and abilities on take on tasks and determine whether or not they are able to continue with this work for Sprint 2. This is a great way for the team to reflect on how to become more effective, then fine tune and adjust it behaviour accordingly. The team found that by having these retrospectives, they significantly improved their work ethic by the time Sprint 2 came about, indicating the importance of reflection in team work.

# System Advantages

Many advantages will come with the introduction of the proposed vaccine management system. One of the main advantages will be the great improvement with the organisation of the vaccination process. This entails that the healthcare workers will have to record when a vaccine is given, how many vaccine doses are left as well as who it was given to. This system allows for a much easier and accurate way of recording these points thus ensuring that data is stored accurately. The system will also improve the experience not only for the healthcare workers but for the general public also. As the system comes with a feature that allows the public to view information on the vaccines boosting public confidence in the vaccine's safety. Also provides them with an easy application process where the time slotting and confirmation is automated by the system lowering the risks for human error. The system will also automatically send the notification for patients for their vaccination allowing for better organization for the patients as well. The system will allow the health workers to view the application details as well as let the health workers check for the identity of the patient lowering the risk of giving vaccines to the wrong person. The system will also let the health workers and government keep track of dosage amounts as well as the vaccination rates. Providing the government important data to see how the country is keeping on track with the vaccination rollout. Once the patient vaccination process completed, the system will generate a vaccination certificate as an evidence that the patient has been vaccinated. In general, the system should make the process much faster and efficient.

# Possible effects if the project fails:

If the system were to fail there would be very large delays for both health workers and patients. As firstly the application system will have to be done manually or completely scrapped causing large lines and confusion with the vaccination. The health workers will have to manually make sure they give the correct doses to the right person while recording how many doses were given. Thus leading to a lot of chances for human error. This could lead to incorrect data on who has received the dose, how many doses are left and if the hospital would need to order more from the government. This could cause problems for the government as they will face more problems with keeping the supply of the vaccines going to the correct places that need them. As many hospitals and vaccination centres could lose track of their vaccination count if the system were to fail. In conclusion the failure of the system will severely slow down the vaccination process.


