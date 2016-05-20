# Sprint Retrospective, Iteration 4

Context Project: Health Informatics  
Group: HiVR
| User story   | Task     | Task Assigned to | Estimated Effort per Task | Actual Effort per Task | Done | Notes |
| :----------- | :------- | :--------------- | :------------------------ | :--------------------- | :--- | :---- |
| As a user we want to see how to use the repositories | Update the README files | Adriaan | 1 | 2 | Yes | */readme |
| As a developer we want to see how to use the repositories | Job to run unit tests and collect results | Boris | 2 | 2 | No | ContinuousIntegration/pull/ 2&3 Running is finished, no collection of results yet. |
|  | Job to compile Unity project | Boris | 4 | 6 | Yes | ContinuousIntegration/pull/3 |
|  | Job to compile Client C# project | Boris | 4 | 4 | Yes | ContinuousIntegration/pull/2 |
| As a developer I want to have feedback from the professor and CleVR | Make a demo  | Carlos | 4 | 3 | Yes | non-git |
|  | Mail CleVR whether our application is fullscreen or whether other programs should be able to claim screen space beside it  | Leon | 1 | 1 | Yes | non-git |
|  | Add in demo what are goals for next week are and what went wrong this week | Carlos | 1 | 1 | Yes | non-git |
|  | Send the demo for feedback to CleVR | Carlos | 1 | 1 | Yes | non-git |
| As a developer we want to connect the GUI with Unity | Create a TCP connection from Unity to GUI Client | Adriaan | 8 | 10 | Yes | CleVR-Map/ConnectNetwork & HiVRClient/ConnectNetwork |
|  | Make a Unity plugin that collect relevant information from the objects | Boris | 8 | 10 | Yes | CleVR-Map/pull/5 |
|  | Send objects according to the protocol from the Unity plugin to the GUI Client | Adriaan/Boris | 16 | 10 | No | Not yet finished because it took a lot of research work |
|  | Implement a JSON-parser library for the messages received over network | Leon/Wim | 4 | 0 | No | |
|  | Test the Unity plugin | Adriaan/Boris | 6 | 5 | No | Collection of unity objects is mostly tested but not on git because the tests are not yet reliable |
|  | Test whether we can break the synchronization of the implementation the protocol | Carlos | 6 | 0 | No | |
| As a therapist we want to see a static map of a 3D environment | Make a View that can render various objects (like walls, benches and actors) on screen | Leon/Wim | 16 | 20 | No | Nearly finished & HiVRClient/enhancement/render_map |
|  | Make a ViewModel that feeds those objects to the View | Wim/Leon | 16 | 20 | No | Partly finished & HiVRClient/enhancement/render_map |
|  | Display walls in any shape | Leon | 4 | 1 | No | |
|  | Display Bench/Tree/Car/TV | Leon | 3 | 0 | No | |
|  | Find free Icons to use for objects on the custom canvas | Adriaan | 2 | 0 | No | Was not needed anymore because we will be using colored squares and in a later stadium vectors |
| As a therapist I want to be able to see the patients location in the virtual world | Display the patient location | Adriaan | 2 | 0 | No | |
|  | Design a natural, clear way to display walk- and FoV rotation of the patient | Carlos | 4 | 4 | No | non-git |
|  | Display the patient walking orientation | Carlos | 4 | 2 | No | Waiting for unity data |
| As a student we need to update our Architecture Design | Update Design Goals | Carlos | 2 | 2 | Yes | HiVR/deliverables/tree/master/sprint4 |
|  | Update Subsystem Decomposition/Hardware, software mapping | Carlos | 2 | 2 | Yes | HiVR/deliverables/tree/master/sprint4 |
|  | Update Persistent data management, concurrency | Carlos | 2 | 2 | Yes | HiVR/deliverables/tree/master/sprint4 |
| As a therapist I want to be able to see the moving objects in the virtual world | Update Actors to current positions | Wim | 6 | 0 | No | |
|  | Display Actors in the virtual world | Wim | 3 | 0 | No | |
| As a therapist I want to be able to see the patients field of view in the virtual world | Collect the FoV from Unity | Boris | 4 | 5 | Yes | CleVR-Map/pull/5 |
|  | Send the FoV to GUI client | Boris | 2 | 0 | No | |
|  | Display the FoV | Carlos | 2 | 0 | No | |
| As a therapist I want to be able to see the state of objects in the virtual world | Display the tv screen text | Carlos | 2 | 0 | No | |
|  | Display if the car siren is on/off | Carlos | 2 | 0 | No | |
|  | Display the emotions of the actors | Carlos | 4 | 0 | No | |
| As a developer we want to have a properly tested software product | Report results back to Github PR | Adriaan | 2 | 1 | No | This was not possible until the building on the CI was finished. |
|  | Achieve 80% code coverage by writing missing tests | Wim | 3 | 0 | No | |

## Main Problems Encountered
### Not spent enough time
#### Description: We should have spent more time on the project instead of other things. The cause was partly: Exams, sickness, personal things
Reaction: More contact hours. We agreed to meet every tuesday and thursday from now on in the morning. And we try to anticipate on the amount of available hours each week in our sprint planning (eg. Exam)
### Not enough communication Wim/Leon
#### Description: Task that are really intertwined with multiple people need to be intensively communicated
Reaction: Divide the task in subtasks and communicate through, for example, Skype about the progress
### WPF remains a challenge
#### Description: WPF remains fairly complicated since we've never used it before. It takes a lot of time to research various things and that time would've been better spent writing actual code.
Reaction: We should only implement a basic version and we shouldn't spend time researching WPF for unnecessary stuff

## Adjustments for the next Sprint
Meet every tuesday and thursday from now on to work and communicate more closely.  
Anticipate the amount of available hours next week and adjust the sprint to it. Next week will be a exam of ATB. So that means less hours in the sprint.  
More communication if you share a subtask. The person that is responsible for the task is responsible for the communication.
