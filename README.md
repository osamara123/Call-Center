The American University in Cairo - School of Sciences and Engineering
Department of Electronics and Communication Engineering
Course Title: Telecommunication Systems (ECNG 4308) – Fall 2024
Instructor: Dr. Yasser Gadallah
A VoIP-based Call Center/PBX
I. Project Description
In this project, 3-member teams will be using the “Asterisk communications center” as the base
of a VoIP based call center system. It is required to design and implement a call center for a startup
company to receive and direct customer calls to the available agents. The agents are grouped into
Arabic, English and French speakers. Therefore, your system has to be able to provide an options
menu to the customers (e.g. to choose the appropriate language). It should then handle the callers’
waiting queue in a fair manner.
In addition, the agents as well as other employees inside the company can internally use the system
as a PBX to communicate with each other.
Agents should be able to divert external customer calls to the Technical Support office but cannot
divert a call to the company’s CEO or any department manager, except the manager of the call
center department (e.g. for escalation/complaint purposes). It is also required to make sure that the
CEO can call any person within the company. Only managers can call the CEO.
During Rush hours, the system queue could be congested, thus the customer must be offered an
option to provide his/her number and hang up. The system will then call that customer back as
soon as an agent is free. The customer has the option to feed the system with an alternative phone
number (in addition to any previously stored phone number for this customer). After the customer
adds the number, the system must playback the entered number for confirmation purposes.
To ensure high quality service, all inbound calls have to be recorded; an option that should be
available to the PBX as well (i.e. recording internal calls should be made optional (configurable)
but recording customer calls is mandatory). In addition, the system must call back the users after
a while to gauge customer satisfaction. The system must save the call history logs and information
about calls in case they need to be investigated later by system administrators/designers when/if
needed. The system must have a user-friendly interface for its operations (e.g. as opposed to having
to edit files manually, etc.).
II. Project Milestones and Guidelines
You are required to design and implement the system as described above, while each team is
additionally required to implement a unique system feature (see the group-specific feature list at
the end of this file) according to the following milestones:
1- Phase I: System installation and design
• Install the Asterisk communication server
• Create simple configurations and illustrate this via establishing a simple call
• Prepare a document to describe your design (see Section III.3)
2- Phase II: Overall system implementation
• Implement all the required features
• Implement the team-specific feature
• Complete the design document that you started in Phase I
• Illustrate “call diverting” rules
• Prepare a full physical system demo that includes the necessary PC
stations/servers, phones, etc.
III. Instructions and Deliverables
1- Do NOT use any assistive tools over Asterisk.
2- Submit all configuration files, database and voice files (as applicable) as a zip file on
Canvas (in Phase II). Only one submission per team is required.
3- Submit a design document that includes at least the following sections (Phases I and II):
a. An introduction which includes the objectives/features of your system
b. A complete system design description. This includes a description of each system
element. You need to include a block diagram of the system to illustrate the
relationships among its components.
c. A description of the system functionality (i.e. system operation procedures in a
“user manual” style).
d. You must include the references that you used to obtain the information for your
design in your document.
e. Any configuration and coding information on which you have based the system or
parts of the system.
IV. Project Deadlines (missing any deadline results in losing 1 mark, each)
1- Teams should be formed (use the groups that have been created on Canvas) by Thursday
October 3, 2024).
2- The selected unique feature (i.e. the group-specific feature from the feature list) by each
team must be emailed to the professor (ygadallah@aucegypt.edu) by Monday October 14,
2024 @5:00PM. In case of selecting a feature by more than one team, the rule of firstcome-
first-served will be applied based on the received emails’ timestamps.
3- Phase I: Preliminary “System description and functionality” document submission on
Canvas: Monday October 28, 2024 @5:00 PM. We will then schedule some time to discuss
what you have reached, up to this point. The students are expected to have fully completed
Phase I requirements as specified above.
4- Phase II: Delivery of the (system design document + zip file of configuration files + any
developed software) will be via Canvas by Monday November 25, 2024 @5:00 PM. We
will then schedule some time to demo your FINAL products.
V. Assessment
During a day/time to be agreed on, each team will be given 10 minutes sharp to present their system
functionality (we will do this twice: once for Phase I and once for Phase II). Assessment will be
done on a competitive basis among teams.
a. Group assessment: 20 marks [If a student does not contribute, he/she does not earn
group marks!]
i. System functionality: 8 marks
ii. Unique feature functionality: 3 marks
iii. System usability: 5 marks
iv. Documentation: 4 marks
b. Individual student assessment: 10 marks
i. Knowledge of the system and code: 5 marks
ii. Contribution to the work (each student must indicate her/his contribution
precisely!): 5 marks
Students who plagiarize will be subject to penalties as outlined in
www.aucegypt.edu/academics/integrity/Students/Pages/default.aspx.
Group-specific Unique Features
Select only one of the following features for your group. Email the feature number and full
feature description to ygadallah@aucegypt.edu by the deadline specified in the “project
deadlines” section. Features will be allocated on a first-come-first-served basis, as described
above.
1. Feature 1
The Company starts a marketing campaign by sending promo codes to random users. The System
must therefore be able to send SMSs to users.
2. Feature 2
The company allows some employee mobility while handling customer calls, e.g. an employee,
while handling a customer call, needs to check some files at a different desk and hence may
continue the call from another station. The system must offer this option to promote the
environment of mobility and flexibility.
3. Feature 3
The Company work flow depends greatly on mini-meetings, so the system must offer an option of
several employees joining one call.
4. Feature 4
If an employee is not sitting at his/her desk, the system must allow a caller to leave a message to
that employee telling him the purpose of the call and how the caller may be reached later.
5. Feature 5
The company’s work depends mainly on teamwork. Hence, if an employee is getting a call at
his/her number but he/she is not available at his/her desk while another colleague is available to
answer, the other employee must be able to pick up the call at his/her station instead of letting the
caller hang up and try another attendant.
6. Feature 6
When multiple customers call the company at the same time, the system should place them in a
queue, and prioritize their calls based on predefined criteria. For example, VIP customers or
customers calling with urgent issues should be prioritized and their calls routed to the front of the
queue.
7. Feature 7
Supervisors can listen in on live calls and “whisper” advice or instructions to agents without the
customer hearing. This is useful for training new agents or guiding them during difficult calls.
