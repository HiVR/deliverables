# Sprint Retrospective, Iteration 6

Context Project: Health Informatics  
Group: HiVR
| User story   | Task     | Task Assigned to | Estimated Effort per Task | Actual Effort per Task | Done | Notes |
| :----------- | :------- | :--------------- | :------------------------ | :--------------------- | :--- | :---- |
| As a developer we want to have a clear user interface so that the therapist can easily use the software | Make a design interaction plan | Carlos | 8 | 8 | Done | |
| As a developer we want to see how to use the repositories | Job to run unit tests and collect results | Boris | 3 | 4 | Done | |
| As a developer I want to have feedback from the professor and CleVR | Make a demo  | Carlos | 4 | 4 | Done | the codebase was restructured, so the demo had to be updated accordingly | 
|  | Add in demo what are goals for next week are and what went wrong this week | Carlos | 1 | 1 | Done | |
|  | Send the demo for feedback to CleVR | Carlos | 1 | 1 | Done | |
| As a developer we want to exchange information between the client and the server by connecting the GUI with Unity | Send dynamic objects from Unity | Boris | 14 | 12 | Done |   |
|  | Test the Unity plugin | Adriaan | 8 | 3 | Not Done |Sickness of Adriaan |
|  | Test whether we can break the synchronization of the implementation the protocol | Carlos | 6 | 0 | Not Done | There was no synchronization yet to test |
|  | Display error when connection fails | Wim | 5 | 2 | Not Done | Connection was not there yet, so it couldn’t fail|
| As a therapist I want to be able to see the patient's location in the virtual world | Display the patient location | Leon | 10 | 0 | Not Done | This actually turned out as implementing moving actors, because we discovered this was a logical step-up to displaying the patient |
|  | Design a natural, clear way to display walk- and FoV rotation of the patient | Carlos | 4 | 1 | Not Done | Dependent on the patient's location |
|  | Display the patient walking orientation | Carlos | 4 | 1 | Not Done | Dependent on the patient's location, worked on  |
| As a developer we want to avoid crashes by having a properly tested software product | Test dotCover and look whether it is useful for our project | Wim | 3 | 3 | Done | Only local for now on Wims machine |
|  | Achieve 80% code coverage by writing missing tests | Wim | 6 | 3 | Not Done | Good testing is important! |
|  | Report results back to Github PR | Adriaan | 2 | 0 | Not Done | Sickness |
| As a therapist we want to see a static map of a 3D environment | Display TV | Leon | 3 | 0 | Not Done | This was less important than displaying the actors/patient|
| As a student we need to update our Architecture Design | Update Design Goals | Carlos | 2 | 2 | Done  | |
|  | Update Subsystem Decomposition/Hardware, software mapping | Carlos | 2 | 1 | Done | Update accordingly to new Data management|
|  | Update Persistent data management, concurrency | Carlos | 2 | 0 | Not Done | |
| As a therapist I want to be able to see the moving objects in the virtual world | Update Actors to current positions | Wim | 16 | 20 |  Done | Was quite a challenge to do this. Still will rely on the actual network coordinates |
|  | Display Actors in the virtual world | Wim  | 5 | 2 | Done |  |
|  | Interface to calculate differences between actor locations | Adriaan  | 5 | E | |
| As a therapist I want to be able to see the patient's field of view in the virtual world | Send the FoV to GUI client | Boris | 2 | 3 | Done | Hard to implement but not a very important requirement |
|  | Display the FoV | Carlos  | 2 | 0 | Not Done | |
| As a therapist I want to be able to see the state of objects in the virtual world | Display the tv screen text | Leon | 2 | 0 | Not Done | |
|  | Display if the car siren is on/off | Carlos  | 2 | 1 | Not Done | Dependent on connection with unity |
|  | Display the emotions of the actors | Carlos | 4 | 0 | Not Done | Dependent on connection with unity | 

Problems:
We had two cases of sickness this week.

Solution: There is no clear-cut solution for this, except hoping they will be better next week. The rest of the group just worked on their own code.

For the next sprint:
Focus more on the bare essentials, instead off on the less necessary functions.
