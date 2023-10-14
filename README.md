# ZooSeeker

App developed for the San Diego Zoo in UCSD CSE 110. Visitors can use the app to create lists of landmarks at the zoo and get real-time directions to each exhibit.

# Route Planning
The ZooSeeker home screen features a list of all exhibits at the San Diego zoo. Add and search for exhibits to visit, then tap **Get Directions** to start navigation.
**Back** will return to the home screen, **Show List** will display all selected locations once at least one exhibit is selected, and **Clear** will clear the current list. **Get directions** will begin the navigation process.

Home Screen:

![Home Screen](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/SearchScreen.PNG?raw=true)

Search Bar:

![Search Bar](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/SearchBar.PNG?raw=true)

Show List:

![Show List](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/ShowList.PNG?raw=true)

Selections:

![Selections](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/SearchScreenSelections.PNG?raw=true)

Clear List:

![Clear List](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/ClearList.PNG?raw=true)

# Navigation
ZooSeeker will automatically calculate the recommended path to all selected exhibits which minimizes walking distance and provide a route summary. **Back** will return to the previous navigation screen, **Next** will advance to the next destination, and **Skip** will skip the next exhibit on the list. Brevity of directions can be toggled with **Brief** and **Detailed** on the top right.

Route Summary:

![Route Summary](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/RouteSummary.PNG?raw=true)

Navigation Screen:

![Navigation Screen](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/Nagivation.PNG?raw=true)

Brief Directions:

![Brief Directions](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/BriefDirections.PNG?raw=true)

Detailed Directions:

![Detailed Directions](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/DetailedDirections.PNG?raw=true)

# Mocking
Automatic and manual location mocking can be done with **Mock**, which will detect invalid coordinates and prompt to re-plan route pathing if the current coordinates are too far from the previous starting point.

Location Prompt:

![Location Prompt](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/MockLocationPrompt.PNG?raw=true)

Mocking:

![Mocking](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/MockLocationEntry.PNG?raw=true)

Location Error:

![Location Error](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/MockLocationError.PNG?raw=true)

Re-routing:

![Re-routing](https://github.com/HuangMichael94/ZooSeeker/blob/main/images/MockLocationReplan.PNG?raw=true)
