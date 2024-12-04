# CS360
Event Tracking Application

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
This application is meant to record and save user input to keep track of events for the user and notify them on the day of an event. The application can currently create and edit events in 
the list, but not delete or save them to a database. The application will also incorporate user profiles to be saved on the database.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? 
## How did your UI designs keep users in mind? Why were your designs successful?
Many screens were needed to accomplish these features including a login, register, grid view, notification settings,  and edit event screen. The login screen would work so long as the user's information had been registered previously to the database. The registered screen takes the user information and puts it into the database as a new list. The grid view is where the user can view saved events and edit them as they like. The notification settings screen is where the user would choose to be notified on the event dates. The simplicity of the screens helped ensure a straightforward uncomplicated user experience. They were successful by users understanding operations with no need for an explanation.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
It helped to break down the essentials of the application, starting with the main screen, the grid view of events, and developing the branches off of that initial screen. Once the grid view was able to display a list of pre-made events, then it was easy to incorporate the add screen. When the add screen was completed it was easier to incorporate an edit screen. After that creating the menu setting was much easier to incorporate.

## How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
My testing was mostly conducted through the use of tests to account for human error, which was a positive thing as my design had to be adjusted several times to make the best-looking and functioning grid view that accounted for user clicks on the grid view item rather than the button I had wanted to implement in the design.

## Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
From initial planning to finalization, I realized that the date input would have to be adjusted to create a normalized string output that would make development much easier than trying to work with the Calendar or Date class specifically in use with a database. I was able to allow the user to select a date on a pop-up calendar which would then convert into a string that is easier to work with.

## In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
I believe I was able to demonstrate my knowledge and skill best when developing the add and edit functions of the application, while they are currently meant to add to the ArrayList object, I think I was able to determine how that was done quite expertly and will be able to convert those functions to database use much easier.
