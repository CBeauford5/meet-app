# meet-app

## Objective

To build a serverless, progressive web application (PWA) with React using a test-driven development (TDD) technique. The application uses the Google Calendar API to fetch upcoming events.

## Project Requirements

- filter events by city
- show/hide event details
- specify number of events
- use the app offline
- add an app shortcut to the home screen
- display charts visualizing event details 

## User Stories

- As a user, I would like to be able to filter events by city so that I can see the list of events that take place in that city.

- As a user, I would like to be able to show/hide event details so that I can see more/less information about an event.

- As a user, I would like to be able to specify the number of events I want to view in the app so that I can see more or fewer events in the events list at once.

- As a user,I would like to be able to use the app when offline so that I can see  the events I viewed the last time I was online.

- As a user, I would like to be able to add the app shortcut to my home screen so that I can open the app faster.

- As a user, I would like to be able to see a chart showing the upcoming events in each city so that I know what events are organized in which city.


## Test Scenarios (Given-When-Then)

Feature 1: Filter Events By City

Given: the user has launched the event application and is on the events listing page
When: the user selects a specific city from the available city options in the filter menu
Then: the events listing page refreshes, displaying only the events that are located in the selected city

Feature 2: Show/Hide Event Details

Given: the user is viewing the event details page 
When: the user clicks on the "more info" button to close or open additional information  
Then: the event details section either expands or collapses, showing or hiding additional information about the event, respectively

Feature 3: Specify Number of Events

Given: the user is on the events listing page
When: the user inputs a specific number or selects a predefined option from a drop-down menu to specify the desired number of events to be displayed
Then: the events listing page refreshes, displaying the specified number of events

Feature 4: Use the App When Offline

Given: the user has previously accessed the event application and has an active internet connection
When: the user loses internet connectivity or enables airplane mode
Then: the event application displays a message indicating that the user is offline and some features may be limited or unavailable and previously viewed events and cached data are still accessible

Feature 5: Add an App Shortcut to the Home Screen

Given: the user has installed the event application on their mobile device
When: the user long-presses the app icon or accesses the app settings 
Then: the user is presented with an option to add a shortcut to the home screen and upon confirming, the app icon appears on the home screen for easy access

Feature 6: Display Charts Visualizing Event Details

Given: the user is viewing the event details page
When: the user taps on a "view charts" button or a specific tab within the event details page
Then: the application retrieves relevant data and generates visually appealing charts, presenting them to the user within the event details page to provide additional insights or statistics about the event.