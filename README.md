# The American University in Cairo - School of Sciences and Engineering
- Department of Electronics and Communication Engineering
- Course Title: Telecommunication Systems (ECNG 4308) – Fall 2024
- Instructor: Dr. Yasser Gadallah

### A VoIP-based Call Center/PBX
# I. Project Description

##In this project, 3-member teams will be using the “Asterisk communications center” as the base
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

# II. Project Milestones and Guidelines

##You are required to design and implement the system as described above, while each team is
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


# Additional Feature
When multiple customers call the company at the same time, the system should place them in a
queue, and prioritize their calls based on predefined criteria. For example, VIP customers or
customers calling with urgent issues should be prioritized and their calls routed to the front of the
queue.
