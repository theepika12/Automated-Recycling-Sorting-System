# Automated-Recycling-Sorting-System
This project involved developing an automated recycling system using a robotic system to classify, transport, and deposit containers into their designated recycling bins. The project consisted of a modelling sub-term and and a computing sub-team, which I was apart of.

## Project Objectives

The computing sub-team was responsible for:
- Classifying containers and following a specified path to the correct bins
- Developing code to load, transfer, deposit, and return containers
- Optimizing the code for efficiency and accurarcy

## System Functions
The recycling system was designed to perform four main actions:
1. Load - Load containers onto the hopper
2. Transfer - Move containers toward their designated bins
3. Deposit - Deposit containers into the correct bin
4. Return Home - Return the system to its initial position

The system used several sensors to identify and navigate the containers:
- Load sensor
- Line-following sensor
- Colour sensor
- IR sensor

## Design Constraints

The system had to operate within several constraints:
- The hopper could hold a maximum of three containers
- An additional container would only be loaded if it was the same type as the previous container

## System & Environment

The system was developed and tested using **Quanser Interactive Labs**, which provided a virtual environment for simulating the recycling system.



## Final Outcome

The completed system successfully handled the main recycling process:
- Loaded containers onto the hopper
- Identified and moved containers through the system
- Deposited containers into their respective bins
- Returned to the initial position

The system was able to efficiently coordinate the different stages of the recycling process using sensor-based inputs and programmed functions.

## My Role - Administrator

As the Administrator for the computing sub-team, I helped coordinate the team's progress while contributing to the development of the system's code.

### Administrator Contributions
- Monitored the progress of team deliverables to help ensure deadlines were met
- Ensured team members were aware of project deadlines and expectations
- Helped coordinate work throughout the development process

### Technical Contributions
- Created pseudocode for the final program
- Developed the transfer function
- Assisted with developing the code for the physical environment
- Contributed to the overall programming and testing process

## Tools & Technologies
- **Python** - Programming and system control
- **Quanser Interactive Labs** - Virtual robotic system development and testing
- **Sensors** — Load, line-following, color, and IR sensors

## Skills Demonstrated

### Technical Skills
- Python Programming
- Sensor Integration
- Pseudocode Development
- System Testing

### Professional Skills
- Project Coordination
- Team Collaboration
- Oral Communication
- Time Management
- Problem-Solving

## Key Takeaways

This project taught me the importance of clearly defining responsibilities within a team. A missed deliverable caused by confusion about individual contributions showed me the value of establishing clear roles and regularly checking project progress.

The project also showed me the importance of designing code that can adapt to different environments. Although our deposit function worked in the specific environment we were given, it was not easily transferable to other settings. A better approach would have been to use sensors to detect the bin's location before depositing the container.

Overall, this project strengthened my programming, robotics, and problem-solving skills while also improving my ability to coordinate tasks and adapt solutions when challenges came up.
