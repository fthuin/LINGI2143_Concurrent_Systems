# LINGI2143 Concurrent systems: models and analysis

## Assignment 1: A Leader Election Protocol - Modeling Phase
Note: 8/10

Building FSP in LTSA to create the corresponding LTS. 

## Assignment 2: A Leader Election Protocol - Verification Phase
Note: 7/10

Verifying fairness and liveness properties over the build LTS with LTSA.

## Assignment 3: A Police Department
Note: 7.5/10

Modeling a Petri Net using TINA with the following specifications:

* The police department is staffed by a limited number of inspectors, officers, coroners and clerks. Inspectors only handle criminal affairs, officers patrol and handle incidents, coroners check victims on crime scenes, and clerks stay at the office and handle administrative tasks only. Any clerk can perform any clerical task.

* Patrols consist of two officers in a police vehicle. Vehicles are in limited supply. Patrols may be formed and leave the department at any time, and may come back at any time when they are not handling an incident.

* Phone calls asking for police intervention are dispatched by clerks. Phone calls can be of two types: incident calls or crime calls. In both cases, an available clerk receives and records the call, then contacts a patrol that will intervene on the scene. The clerk is then available again; he does not wait for the result of the intervention.

* For incident calls, the patrol only goes on the scene and handles the incident. It then contacts the department by radio to report on the incident. At the department, an available clerk receives and records the report. The patrol and the clerk are then available again.

* For crime calls, the patrol must rst get to the crime scene and wait for a coroner and a police inspector to arrive. When the crime scene has been investigated and cleared, everyone goes back to the office. The coroner and one of the officers are available for further duties, while the other officer and the inspector join up with an available clerk to write a report. Everyone is available again once the report is done.
