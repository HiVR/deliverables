# Sprint Backlog, Iteration 4

Context Project: Health Informatics  
Group: HiVR

| User story | Task | Member Responsible for the Task | Task Assigned to | Estimated Effort per Task | Priority(A-E) |
| :--------: | :--: | :-----------------------------: | :--------------: | :-----------------------: | :-----------: |
| As a user we want to see how to use the repositories | Update the README files | Adriaan | Adriaan | 1 | A |
| As a developer we want to see how to use the repositories | Job to run unit tests and collect results | Boris | Boris | 2 | A |
|  | Job to compile Unity project | Boris | Boris | 4 | A |
|  | Job to compile Client C# project | Boris | Boris | 4 | A |
| As a developer I want to have feedback from the professor and CleVR | Make a demo  | Carlos | Carlos | 4 | A |
|  | Mail CleVR whether our application is fullscreen or whether other programs should be able to claim screen space beside it  | Leon | Leon | 1 | A |
|  | Add in demo what are goals for next week are and what went wrong this week | Carlos | Carlos | 1 | B |
|  | Send the demo for feedback to CleVR | Carlos | Carlos | 1 | C |
| As a developer we want to connect the GUI with Unity | Create a TCP connection from Unity to GUI Client | Adriaan | Adriaan | 8 | A |
|  | Make a Unity plugin that collect relevant information from the objects | Boris | Boris | 8 | A |
|  | Send objects according to the protocol from the Unity plugin to the GUI Client | Adriaan | Adriaan/Boris | 16 | A |
|  | Implement a JSON-parser library for the messages received over network | Leon | Leon/Wim | 4 | A |
|  | Test the Unity plugin | Boris | Adriaan/Boris | 6 | C |
|  | Test whether we can break the synchronization of the implementation the protocol | Carlos | Carlos | 6 | C |
| As a therapist we want to see a static map of a 3D environment | Make a View that can render various objects (like walls, benches and actors) on screen | Leon | Leon/Wim | 16 | A |
|  | Make a ViewModel that feeds those objects to the View | Wim | Wim/Leon | 16 | A |
|  | Display walls in any shape | Leon | Leon | 4 | A |
|  | Display Bench/Tree/Car/TV | Leon | Leon | 3 | A |
|  | Find free Icons to use for objects on the custom canvas | Adriaan | Adriaan | 2 | C |
| As a therapist I want to be able to see the patients location in the virtual world | Display the patient location | Adriaan | Adriaan | 2 | A |
|  | Design a natural, clear way to display walk- and FoV rotation of the patient | Carlos | Carlos | 4 | B |
|  | Display the patient walking orientation | Carlos | Carlos | 4 | C |
| As a student we need to update our Architecture Design | Update Design Goals | Carlos | Carlos | 2 | B |
|  | Update Subsystem Decomposition/Hardware, software mapping | Carlos | Carlos | 2 | B |
|  | Update Persistent data management, concurrency | Carlos | Carlos | 2 | B |
| As a therapist I want to be able to see the moving objects in the virtual world | Update Actors to current positions | Wim | Wim | 6 | B |
|  | Display Actors in the virtual world | Wim | Wim | 3 | B |
| As a therapist I want to be able to see the patients field of view in the virtual world | Collect the FoV from Unity | Boris | Boris | 4 | C |
|  | Send the FoV to GUI client | Boris | Boris | 2 | C |
|  | Display the FoV | Carlos | Carlos | 2 | C |
| As a therapist I want to be able to see the state of objects in the virtual world | Display the tv screen text | Carlos | Carlos | 2 | C |
|  | Display if the car siren is on/off | Carlos | Carlos | 2 | C |
|  | Display the emotions of the actors | Carlos | Carlos | 4 | D |
| As a developer we want to have a properly tested software product | Report results back to Github PR | Adriaan | Adriaan | 2 | C |
|  | Achieve 80% code coverage by writing missing tests | Wim | Wim | 3 | E |
