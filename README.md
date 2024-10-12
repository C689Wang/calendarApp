# QuestFlow

This repo is only a guide and show-and-tell of the project. Code can be shown on request. See below for contact information.

## Goal
Develop a full-stack application that assists Waterloo students with course planning for upcoming semesters by preventing and detecting time conflicts, providing a calendar view of their schedule, along with functionality to share schedules with peers/friends. 

## Project Proposal


## Getting Started
Check out the user guide or view the instructions for running the application.

## Detailed User Guide


## Instructions for Running and Building


## Architecture & Design


## Reflections on Practices


## Sources
The following links are sources that were used to build the project: <br>

Calendar Layout: <https://danielrampelt.com/blog/jetpack-compose-custom-schedule-layout-part-1/>
   - The logic for implementing the calendar layout including drawing each course to the right time. <br>

Fuzzy String Searching: <https://github.com/willowtreeapps/fuzzywuzzy-kotlin>
   - Originally, I was trying use this github library as an implementation dependency, but it turns out that the library was no longer maintained and the importing it was not an option. As such, I had to fork their repository to my own repo. <br>

Drag and Drop: <https://blog.canopas.com/android-drag-and-drop-ui-element-in-jetpack-compose-14922073b3f1>
   - The blog was used to help with implementing the drag and drop feature for the custom calendars. <br>

OptaPlanner Logic: <https://stackoverflow.com/questions/71572097/is-optaplanner-scheduling-ai-suitable-for-optimising-a-college-schedule>
   - The StackOverflow post was used to help use implementing the constraints for the course schedule optimization where the hard constraint was no overlapping courses, the medium constraint was minimize working days and the soft constraint was minimizing gaps between courses on the same day. <br>

## Support
For any inquiries, please email <calendarappgcp@gmail.com>.
