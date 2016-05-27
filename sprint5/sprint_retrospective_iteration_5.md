# Sprint Retrospective, Iteration 5

Context Project: Health Informatics  
Group: HiVR

| User story   | Task     | Task Assigned to | Estimated Effort per Task | Actual Effort per Task | Done | Notes |
| :----------- | :------- | :--------------- | :------------------------ | :--------------------- | :--- | :---- |
| As a developer we want to see how to use the repositories | Job to run unit tests and collect results | Boris | 3 | 0 | No | |
| As a therapist we want to see a static map of a 3D environment | Make a View that can render various objects (like walls, benches and actors) on screen | Leon/Wim | 10 | 10 | Yes | HiVRClient/pull/13 |
|  | Make a ViewModel that feeds those objects to the View | Wim/Leon | 16 | 16 | Yes | HiVRClient/pull/13 | 
|  | Display walls in any shape | Leon | 4 | 5 | Yes | HiVRClient/pull/15 |
|  | Display Bench/Tree/Car/TV | Leon | 3 | 7 | Yes | Not the TV. More time because researching took more time. & HiVRClient/pull/15 |
| As a developer I want to have feedback from the professor and CleVR | Make a demo  | Carlos | 4 | 3 | Yes | non-git |
|  | Add in demo what are goals for next week are and what went wrong this week | Carlos | 1 | 1 | Yes | non-git |
|  | Send the demo for feedback to CleVR | Carlos | 1 | 1 | Yes | non-git |
| As a developer we want to connect the GUI with Unity | Send objects according to the protocol from the Unity plugin to the GUI Client | Adriaan/Boris | 16 | 16 | Yes | HiVRClient/pull/14 & CleVR-map/pull/9 |
|  | Implement an object serializer library for the messages received over network | Adriaan/Boris | 10 | 12 | Yes | HiVRClient/pull/14 & CleVR-map/pull/9 |
|  | Test the Unity plugin | Adriaan/Boris | 6 | 0 | No | |
|  | Test whether we can break the synchronization of the implementation the protocol | Carlos/Wim | 6 | 0 | No | |
| As a therapist I want to be able to see the patients location in the virtual world | Display the patient location | Adriaan | 2 | 0 | No | |
|  | Design a natural, clear way to display walk- and FoV rotation of the patient | Carlos | 4 | 2 | No | Not finished because important that it is done right. |
|  | Display the patient walking orientation | Carlos | 4 | 0 | No |
| As a student we need to update our Architecture Design | Update Design Goals | Carlos | 2 | 2 | Yes | HiVR/deliverables/tree/master/sprint5 |
|  | Update Subsystem Decomposition/Hardware, software mapping | Carlos | 2 | 2 | Yes | HiVR/deliverables/tree/master/sprint5 |
|  | Update Persistent data management, concurrency | Carlos | 2 | 2 | Yes | HiVR/deliverables/tree/master/sprint5 |
| As a therapist I want to be able to see the moving objects in the virtual world | Update Actors to current positions | Wim | 6 | 0 | No | |
|  | Display Actors in the virtual world | Wim | 3 | 2 | No | For purpose of the demo we used static actors that will not be used in the final product |
| As a developer we want to have a properly tested software product | Achieve 80% code coverage by writing missing tests | Wim | 6 | 6 | Yes | All code from previous weeks and most of this week is tested & HiVRClient/pull/16 |
|  | Report results back to Github PR | Adriaan | 2 | 0 | No | |
| As a therapist I want to be able to see the patients field of view in the virtual world | Send the FoV to GUI client | Boris | 2 | 0 | No | |
|  | Display the FoV | Carlos | 2 | 0 | No | |
| As a therapist I want to be able to see the state of objects in the virtual world | Display the tv screen text | Carlos | 2 | 0 | No | |
|  | Display if the car siren is on/off | Carlos | 2 | 0 | No |
|  | Display the emotions of the actors | Carlos | 4 | 0 | No |

## Main Problems Encountered
### Code coverage not visible
#### We had issues with using various code coverage tools because they all need licenses and OpenCover was not working for us.
Reaction: Wim will place a screenshot of our Code Coverage every week in the deliverables folder for the TA. And the developers will all get a student license for VS/.Cover

### Sprint planning was too big.
#### As you can see in the above retrospective we have a lot of tasks that have not been finished. This was partly due to exams and partly due to some big tasks having lots of small dependencies.
Reaction: We will start earlier in the week with the tasks that many other tasks depend on. And we will also give these tasks the highest priority in the sprint planning.

## Adjustments for the next Sprint
Wim places screenshot in deliverables folder and searches for a good free alternative for code coverage.  
We also need to take the dependencies between tasks in our sprint planning in account when planning the next sprint.
