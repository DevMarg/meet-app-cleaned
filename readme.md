# Meet App

This is a serverless, progressive web application (PWA) with React using a
test-driven development (TDD) technique. The application uses the Google
Calendar API to fetch upcoming events.

## Feature 1: Show/Hide Event Details

As a user, I should be able to view event details to see more details.

Given: The user is on the event details page. <br />
When: The user interacts with a button associated with an event. <br />
Then: The event details section either expands to reveal more information or collapses to hide it.

## Feature 2: Specify Number of Events

As a user, I should be able to specify the number of events displayed So that I can control how many events I see at once.

Given: The user is on the page listing events. <br />
When: The user selects a specific number of events from a drop-down menu. <br />
Then: The page updates to show the exact number of events chosen by the user.

## Feature 3: Use the App When Offline

As a user, I should be able to use the app offline So that I can access event information without an internet connection.

Given: The user has previously accessed the app while online. <br />
When: The user loses their internet connection. <br />
Then: The app will notify the user of the offline status and display only previously accessed events and cached data.

## Feature 4: Add an App Shortcut to the Home Screen

As a user, I should be able to add the app to my home screen So that I can access the app quickly.

Given: The user has the app installed on their device. <br />
When: The user selects the option to add a shortcut to their home screen. <br />
Then: An icon for the app will appear on the user's home screen.

## Feature 5: Display Charts Visualizing Event Details

As a user, I should be able to see charts visualizing event details So that I can easily understand the distribution of upcoming events.

Given: The user is on the event list page. <br />
When: The user clicks on the "View Charts" button. <br />
Then: A chart displaying details of the events will be shown.

