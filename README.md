# Android-App

/*
This app is written in the Java language:

Description of app:
The app's function is to manage timetables. 
Users may be able to:
- Use different colours for events
- Set alarms for events 
- etc.
Note that the app:
- Allows easy addition of events
- Has an intuitive interface
- Allows users to import whole schedules

Plan:
1. Create a wireframe and storyboard
  - Test the look and feel of the app
2. Develop the backend aspect of the app
  - i.e. Set up servers, databases, APIs, storage solutions etc.  
3. Refine UI
  - Test the flow of the app

Possible expansion (after the initial app has been built) would be to have the same app, but on a different platform/operating system (i.e. iOS)
*/

/*
Step 1:
Wireframe:
- Using Justinmind to design a basic wireframe and hierarchy of information (i.e. which button leads to what screen)
Basic layout of wireframe:

Home screen 
- Shows events in the day
- Allows you to create a new event
  - New event leads to a new page -- "Create an event" screen
- Import a schedule (using various methods: Linking to Google, URL etc.) 
  
Create an event screen
- Allows you to put in date, time (i.e. start and end) and location of event
- Has 2 buttons:
  - Add the event
    - Clicking on this will lead to the "Calendar" screen (The day of the event)  
  - Cancel/ Delete
    - Clicking on this will lead back to the "Home" screen

Calendar screen
- Shows the whole day (Times will be evenly spaced out)

- Considering design of the app:
  - Simplistic
  - Specific colours for each action:
    - Red for "action"
      - Actions include: creating an event
    - Grey for "delete"
    - Blue for Home page
    - 
  - Specific colours for each event
    - Allows the user to set their own colour if they want
    - Default colouring otherwise
      - Blue relating to work/school
      - Red relating to recreational (Maybe?)
      - etc.

- Considering functionality of app:
  - Home page: Today + events today
    - "Create an event" button on the page
  - Create an event page: 
    - Inputs for details about the event
      - Date
      - Time (Duration)
      - Location
      - Recurring?
      - Maybe can include what's happening on the day in relation to the event being created:
        - How long it takes to go from the previous event to the next (i.e. the one being created now)
        - How long it takes to go from the current event (created now) to the next
    - "Create" (leads to the day the event is on) and "Delete" (leads to the Home page) buttons
  - View Calendar page:
    - Overview of the months in the year
    - Months that have passed are "greyed out"
    - Months that have not yet passed are red
    - Month that we are currently in is blue
      - Same for the days (when we "zoom in") -- Days that have passed in the month are greyed out and days that aren't are red. Today will be blue
    - Perhaps allow user to select a day and create an event on that day? (Rather than just the option of putting a date for create an event)
      - In the create an event page, the date will automatically be filled out to the day they were on (which led to the create an event page)
*/
