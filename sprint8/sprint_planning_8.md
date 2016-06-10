# Sprint Planning, Iteration 8

Context Project: Health Informatics  
Group: HiVR

| User story | Task | Member Responsible for the Task | Task Assigned to | Estimated Effort per Task | Priority(A-E) | Reason |
| :--------- | :--- | :------------------------------ | :--------------- | :------------------------ | :------------ | :---- |
| As a team we want to have more people with a thorough understanding of the network so that we ensure its quality | Write Unit Tests for the network| Leon | Leon/Carlos | 10 | A | We think that Wim is more than capable of handling the UI part of the project, so to lessen the effect of the bus-factor we want move project members to the network part for this sprint |
| As a therapist we want to have an exact map of the Unity World displayed so that we can see where the patient is located | Extract the event from Unity at build time which represents the static map | Adriaan | Adriaan/Leon | 10 | A | This is part of displaying a static map, so highest priority. Additionaly, the two teammembers this task is assigned to don’t know yet where to find the map, therefore the high time estimate. |
| As a therapist we want to have an exact map of the Unity World displayed so that we can see where the patient is located | Send the static map over the network | Carlos | Boris/Carlos | 8 | A| This is part of displaying a static map, so highest priority |
| As a therapist we want to have an exact map of the Unity World displayed so that we can see where the patient is located | Receive the static map over the network | Leon | Boris/Leon | 5 | A | This is part of displaying a static map, so highest priority |
| As a therapist we want to have an exact map of the Unity World displayed so that we can see where the patient is located | Display the static map in WPF, with all the static prototypes like benches, trees, cars, buildings, televisions | Wim | Wim | 14 | A | This is part of displaying a static map, so highest priority |
| As a therapist we want to see the immediate vicinity of the patient in the Unity World so that we quickly see everything relevant to the patient | Find a way to focus the view only around the immediate vicinity of the patient | Wim | Wim | 8 | C | This is part of displaying the area around the patient, which rates at second priority |
| As a therapist we want to see the actors moving on the map can see where the actors are moving | Send the actors updated positions over the network | Boris | Boris/Adriaan | 8 | E | This part is already mostly done, but doesn’t work yet on everyones laptop. This is the lowest priority, because it doesn’t have any value without a static map, and more importantly, representatives of CleVR said so. |
