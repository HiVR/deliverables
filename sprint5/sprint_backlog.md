# Sprint Backlog, Iteration 5

Context Project: Health Informatics  
Group: HiVR

| User story | Task | Member Responsible for the Task | Task Assigned to | Estimated Effort per Task | Priority(A-E) | Reason |
| :--------: | :--: | :-----------------------------: | :--------------: | :-----------------------: | :-----------: | :---- |
| As a developer we want to see how to use the repositories | Job to run unit tests and collect results | Boris | Boris | 3 | A | CI is very important for developing. Automating running tests is also very important. |
| As a therapist we want to see a static map of a 3D environment | Make a View that can render various objects (like walls, benches and actors) on screen | Leon | Leon/Wim | 10 | A | This is the basic requirements that CleVR want. A static map. It is important that we finish it this week. |
|  | Make a ViewModel that feeds those objects to the View | Wim | Wim/Leon | 16 | A | |
|  | Display walls in any shape | Leon | Leon | 4 | A | |
|  | Display Bench/Tree/Car/TV | Leon | Leon | 3 | A | |
| As a developer I want to have feedback from the professor and CleVR | Make a demo  | Carlos | Carlos | 4 | A | High priority because the communication with the stakeholders is an important factor in the development process |
|  | Add in demo what are goals for next week are and what went wrong this week | Carlos | Carlos | 1 | B | |
|  | Send the demo for feedback to CleVR | Carlos | Carlos | 1 | C | |
| As a developer we want to connect the GUI with Unity | Send objects according to the protocol from the Unity plugin to the GUI Client | Adriaan | Adriaan/Boris | 16 | A | There will be no data without the Unity connection. This user story is needed for the basic requirements that need to be implemented this week. |
|  | Implement an object serializer library for the messages received over network | Boris | Adriaan/Boris | 10 | A | |
|  | Test the Unity plugin | Adriaan | Adriaan/Boris | 6 | C | |
|  | Test whether we can break the synchronization of the implementation the protocol | Carlos | Carlos/Wim | 6 | C | |
| As a therapist I want to be able to see the patients location in the virtual world | Display the patient location | Adriaan | Adriaan | 2 | A | While showing the static player is imporant, the dynamic FoV and walking is a lower priority |
|  | Design a natural, clear way to display walk- and FoV rotation of the patient | Carlos | Carlos | 4 | B | |
|  | Display the patient walking orientation | Carlos | Carlos | 4 | C | |
| As a student we need to update our Architecture Design | Update Design Goals | Carlos | Carlos | 2 | B | B-priority because it is important that we keep track of our design because it will make developing more clear for the developers and the TA |
|  | Update Subsystem Decomposition/Hardware, software mapping | Carlos | Carlos | 2 | B | |
|  | Update Persistent data management, concurrency | Carlos | Carlos | 2 | B | |
| As a therapist I want to be able to see the moving objects in the virtual world | Update Actors to current positions | Wim | Wim | 6 | B | B-priority because this is also part of the main requirements to have a dynamic map |
|  | Display Actors in the virtual world | Wim | Wim | 3 | B | |
| As a developer we want to have a properly tested software product | Achieve 80% code coverage by writing missing tests | Wim | Wim | 6 | B | Good testing is important! |
|  | Report results back to Github PR | Adriaan | Adriaan | 2 | C | |
| As a therapist I want to be able to see the patients field of view in the virtual world | Send the FoV to GUI client | Boris | Boris | 2 | C | Hard to implement but not a very imporant requirement |
|  | Display the FoV | Carlos | Carlos | 2 | C | |
| As a therapist I want to be able to see the state of objects in the virtual world | Display the tv screen text | Carlos | Carlos | 2 | D | Important requirement for the dynamic map. This is not needed to be finished this sprint. |
|  | Display if the car siren is on/off | Carlos | Carlos | 2 | D | |
|  | Display the emotions of the actors | Carlos | Carlos | 4 | D | |