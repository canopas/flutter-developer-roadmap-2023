<h1 align="center">Flutter Developer Roadmap 2023</h1>

![alt text](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/Flutter-developer-roadmap-header-image%20(1).jpeg)

The Flutter Developer Roadmap 2023 includes **Practical exercises** that cover all the essential concepts used in day-to-day development.
# Guidelines

- Before starting any practical it's important to conduct research and learn the necessary concepts.

- As you progress through the practical exercises, make sure to apply the new knowledge you've gained in subsequent exercises. Try to allocate a maximum 5 days to each practical.


# Table of contents
* [Useful References](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#useful-references)
* [Material Component](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#material-component)
* [Navigation and Routing](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#navigation-and-routing)
* [Networking](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#networking)
* [State management](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#state-management)
* [Depenedency Injection](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#depenedency-injection)
* [Local Storage](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#local-storage)
* [Stream](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#streams)
* [Firestore Database](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#firestore-database)


## Useful References
The references provided are aimed at individuals who have no prior knowledge or experience in developing Flutter apps. They serve as a starting point for beginners in the field, providing basic knowledge that is necessary before diving into Flutter development. 
If you already have knowledge and experience in Flutter development, you may not need to refer to the provided resources. 
* [Set up Flutter Environment](https://docs.flutter.dev/get-started/install)
* [Dart Language](https://dart.dev/language)
* [Version control with Git](https://www.udacity.com/course/version-control-with-git--ud123)
* [Layout in Flutter](https://docs.flutter.dev/ui/layout#1-select-a-layout-widget)
* [Stateful and Stateless widget](https://docs.flutter.dev/ui/interactive#stateful-and-stateless-widgets)
* [State management approaches in Flutter](https://docs.flutter.dev/data-and-backend/state-mgmt/options)
* [App Architecture in Flutter](https://medium.flutterdevs.com/design-patterns-in-flutter-part-1-c32a3ddb00e2)
* [Networking](https://docs.flutter.dev/data-and-backend/networking)
* [Asynchronous programming](https://dart.dev/codelabs/async-await)


# Material Component

### Practical 1
#### Design a fitness app
* Create a Flutter application and Design [Static UI](https://dribbble.com/shots/21236904-Fitness-App-Design).
* Ensure the app's UI is responsive and adapts smoothly to different screen sizes and resolutions.
* Use Flutter's Materials Design 3 to enhance your design process.

### Practical 2
#### Develop a News application
* Home Screen Layout:
  - The home screen should include a toolbar, a floating button, and a section to display news content.
  - Use dummy text and images for the news articles.
    - Toolbar Behavior:
      - Initially, the toolbar should display the app's logo and title.
      - As the user scrolls down to read the news, the toolbar should collapse, allowing more space for content.
      - When the user scrolls back up, the toolbar should expand again, showing the logo and title.
  - Floating Button Animation:
    - Implement an animation for the floating button similar to the example provided [here](https://dribbble.com/shots/3541588-Play-Button-Microinteraction).
    - The button should animate as the user scrolls down and up.
* Utilize eye-catching images or placeholders for the news content.
* Here's [UI for reference](https://cdn.dribbble.com/users/663782/screenshots/3742414/media/67464fde751beb373b4c6fa962edf718.gif).

### Practical 3
#### Implement Survey application
* Home Screen Layout:
  - Display a survey form with the following elements:
    - A question.
    - Four options for each question.
    - A button to proceed to the next question.
* Use a PageView to display questions, allowing users to swipe or use the next button to navigate between questions.
* Track progress as the user answers each question, visually indicating the completion status.
* Survey Completion:
  - Once the user completes the survey, show a pop-up message thanking them.
* Include at least three questions, each with four options, related to the user's shopping experience.
* Utilize eye-catching images or placeholders for the news content.
* Here's [UI for reference](https://cubicleninjas.com/wp-content/uploads/2021/01/NA-2021-Web-Questionnaire-3.jpg)

### Practical 4
#### Fitness Journal
* Develop an app for users to track their fitness activities.
* Use TextFields to allow users to input the details for their workout type(e.g., running, cycling, etc), duration, date, and notes.
* Show all entered workout entries on the home screen in a list.
* Provide options to filter workout entries b by date, type, duration 


# Navigation and Routing

### Practical 5
#### Implement LeaveTracker App 
Create a LeaveTracker application with two screens—Home and Apply-Leave.
* Home Screen:
  - Implement the UI based on the provided reference.
  - Use a dummy image for the person.
  - Add a Floating Action Button (FAB) on the screen.
  - On tapping the FAB, navigate the user to the Apply-Leave screen.
* Apply-Leave Screen:
  - Create a form with `TextFields` for the user to input:
    - Start date of the leave.
    - End date of the leave.
    - Reason for the leave.
  - Add a button to apply for leave. On tapping this button, the user should navigate back to the home screen.
* Show the applied leave details on the home screen after the user submits the form. 
  * The app should be responsive to different resolutions.
* Utilize eye-catching images or placeholders for the UI content.
* Here's [UI for reference](https://github.com/canopas/flutter-developer-roadmap-2023/files/11687291/leaveTracher_ui.zip).

  
### Practical 6
#### SnapCam App
Create an application where users can preview the camera feed, capture images, and save them to the device's gallery.
* Home Screen:
  - Show Camera preview
  - Add a button to capture an image.
  - Add a button to show the captured image preview.
  - Include a save button on the toolbar to save the captured image to the device's gallery.
* Preview Screen:
  - Show the captured image in fullscreen.
  - Add a button to go back to the camera screen.


### Practical 7
#### Implement Navigation for a Messaging application
Create a messaging application with onboard, sign-in, and home screens.
* Onboard Screen:
  - Show a brief introduction to the app's features such as messaging, voice and video calls, and file sharing.
  - Use images, titles, and subtitles to introduce app functionality.
  - Include buttons for navigating to the next/previous features and a skip button to bypass the onboarding flow.
* Sign-In Screen:
  - Allow users to enter their email and password.
  - Add validation to ensure the user enters a valid email address and password.
  - Use a dummy email/password for verification.
  - On successful login, redirect the user to the Home screen.
* Home Screen:
  - Display a screen with three tabs in the persistent bottom navigation bar.
  - Implement screens for each tab with eye-catching UI.
* Ensure that after a successful login, users cannot navigate back to the login screen.
* Use [go_router](https://pub.dev/packages/go_router) for Navigation.
* Here's [UI for reference](https://cdn4.vectorstock.com/i/1000x1000/55/68/chat-message-app-ui-kit-design-vector-34385568.jpg).


### Practical 8
#### Implement Color Pallate App for the web.
Develop an application with two tabs using Bottom Navigation: Home and Palette. 
* Home Screen:
  - Display a list of list tiles, each representing numbers from 1 to 100.
  - Implement navigation to a detail screen when a list tile is tapped.
  - Allow navigation to the detail screen by passing the number in the web URL.
  * Detail Screen (Home Detail):
    - Show the selected number from the list tile.
* Palette Screen:
  - Display a grid list of multiple color palettes.
  - Implement navigation to a palette detail screen when a palette is clicked.
  * Detail Screen (Palette Detail):
    - Display a container with a specific color from the selected palette.
    - Add a button to favorite/unfavorite the color.
* Use go_router for Navigation.
* Utilize eye-catching colors to enhance UI.
* Here's [UI for Reference](https://www.pinterest.com/pin/844706473831200541).

# Networking 

### Practical 9
#### Implement OnlineUserDirectory
Create an application with two screens: Home screen and Detail screen
* Home Screen:
  - Fetch a list of users from the API.
  - Display users in a ListView with drag-and-drop support.
  - Show user summary including name, image, and email.
  - Navigate to the detail screen on user-item click.
  - GET API : http://jsonplaceholder.typicode.com/users
* Detail Screen:
  - Display detailed information about the selected user.
  - Fetch albums for the selected user from the API
  - GET API : https://jsonplaceholder.typicode.com/albums?userId=1
  - Show albums using GridView with placeholder images.
* Utilize the `http` package for making HTTP requests to fetch data from APIs.

### Practical 10
#### Develop RecipeLister application
Create an application with two screens: Home screen and Detail screen
* Home Screen:
  - Fetch a list of recipes from the Yummly API (https://yummly2.p.rapidapi.com/feeds/list).
  - Display recipes in a ListView.
  - Each list item should show the recipe name and a short description.
  - Navigate to the Detail screen by tapping a recipe.
* Detail Screen:
  - Display detailed information about the selected recipe.
  - Show recipe image, name, and full description.
* GET API:  https://yummly2.p.rapidapi.com/feeds/list
* To access API, log in or create an account to obtain an API key.
* Use `dio` for networking.

### Practical 11
#### Develop ImageSaver application
* Create an application that allows users to download an image from a given URL, display the image on the screen, and store the downloaded image file in the device's internal storage.
* Screen Details:
  - Implement a single screen with the following components:
    - A TextField to enter the image URL.
    - Buttons to initiate image download and cancel download.
    - Display download progress using a progress bar.
    - Display the downloaded image in fullscreen once the download is complete.
    - Add a button to save downloaded images to the device's gallery.
* Use `dio` for networking

### Practical 12
#### Implement Drink Explorer
Create an application that allows users to search for mocktail details by name using an API.
* Screen Details:
  - Implement a single screen with the following components:
    - A search bar to allow users to search mocktails by name.
    - Default search text in the search bar should be "mocktail" initially, fetching mocktail data upon app launch.
    - on search, display the ingredients and details of the mocktail.
* GET API : https://www.thecocktaildb.com/api/json/v1/1/search.php?s={mocktail} 
* Use dummy data if required.

 # State Management

 ### Practical 13
 #### Develop the TalkEasy application
Develop an application, TalkEasy, allowing users to send and receive messages between two screens: Sender and Receiver.
* Sender screen:
  - `TextField` for entering a message and Button to send the message.
  - When the user clicks the send button, navigate to the Receiver screen and display the message.
.* Receiver screen:
  - `TextField` for entering a message and Button to send the message.
  - When the user enters a reply message and clicks on the button, the replied message should be sent back to the Sender screen and displayed on the screen.
* Messages should be displayed dynamically on both screens as they are sent and received.
* Use Provider for State Management

### Practical 14
#### Implement MovieDirectory Application
Develop an application, with a Persistent bottom navigation bar with two tabs: Home and Favorite.
* Home screen:
  - Display a grid of movies fetched from an API.
  - Show movie posters with their names.
  - Navigate to a detail screen by tapping a movie.
  * Detail Screen:
    - Show detailed information about a selected movie (e.g., title, description, release year).
    - Add a button to add/remove the movie from favorites.
* On the Favorite screen,
  - Display a list of movies marked as favorites.
  - Provide an option to remove movies from the favorites list.
*  Use flutter_bloc for State Management.
*  GET API: (https://netflix54.p.rapidapi.com)


### Practical 15
#### Implement University directory application
* Develop an application that allows users to browse and search universities from around the world. 
* Home Screen:
  - Display a dropdown menu to select a country.
  - Fetch and display a list of universities from the selected country using an API.
  - Implement search functionality to filter universities based on user input.
* GET API - http://universities.hipolabs.com/search?country={country name}
* Use riverpod for state management.

### Practical 16
#### Develop a Travel application
Create a travel application with three main screens: Destinations, Search, and Settings. 
* Bottom Navigation Bar:
  - Implement a bottom navigation bar with three tabs: Destinations, Search, and Settings.
* Destinations Tab:
  - Display a list of popular travel destinations with images and descriptions.
  - Implement infinite scrolling to load more destinations as the user scrolls to the bottom.
  - Preserve scroll position when navigating between tabs.
  - Use dummy data for destinations.
* Search Tab:
  - Implement a search functionality to search for different destinations.
  - Display a message when the searched destination is not available.
* Settings Tab:
  - Allow the user to customize app settings.
  - Include a toggle button for notification settings and day/night theme settings.
  - Preserve toggle state when navigating between tabs.
* Use dummy data initially for destinations.
* App should preserve the state on tab change
  - Maintain the scroll position in the Destinations tab.
  - Persist search results in the Search tab.
  - Preserve toggle state when navigating between tabs.
* Use the Model-View-ViewModel (MVVM) pattern to separate the business and presentation logic of an application from its user interface (UI).

### Practical 17
#### Create My Journal application
Develop an application where users can add and view their daily thoughts, feelings, experiences, and ideas. 
  - Implement a single screen that displays user entries in a grid format.
  - Include a text field for users to input their thoughts.
  - Add a button to save the user's thoughts.
* Implement Deep linking:
  - On Click of this link https://open.my.app?message={anymessage} from anywhere, the system should open app and show the message from a link
* Use `riverpod` for state management.

### Practical 18
#### Develop MathQuest quiz application
Create a quiz application named MathQuest that presents users with a series of math questions.
* Home Screen:
  - Provide an introduction to the quiz.
  - Add a button to start the quiz.
* Quiz Screen:
  - Ask 10 questions one at a time.
  - For each question, display four answer options.
  - Highlight correct/wrong answers upon submission.
  - Show progress as the user answers the questions.
* Result Screen:
  - Display the number of correct answers out of 10.
  - Show an excellence level based on the score (e.g., poor, good, very good).
  - Add a button to restart the quiz.
* Implement a Dark/Light theme in the app.
* You can use any state management library for state management and image to build eye-catching UI.
* Use injectable and getIt for Dependency Injection.
* Here's [UI for reference](https://cdn.dribbble.com/users/2469034/screenshots/8210470/media/f02da6249ee8c25f187432c73d4eec27.png).
* Write unit test for `ViewModel`.

# Local Storage

### Practical 19
#### Develop Protasker application
* Develop an application with three screens: Login, Home, and Detail screens
* Login Screen:
  - Implement a basic login screen
* Home screen:
  - Display a list of tasks with subtasks and their creation times.
  - Implement a Floating Action Button (FAB) to add a new task.
  - Allow users to mark tasks as complete/incomplete with a button on each list item.
  - Implement swipe-to-delete functionality for tasks.
  - Display a number of pending tasks on the AppBar.
  - Navigate to the Detail screen when a task item is tapped.
* Detail screen:
  - Allow the user to edit this task and subtask.
  - Add a button to save the updated data.
* Use sq_lite to store data
* Display data from SQLite on the home screen.
* You can use any state management library.

### Practical 20
#### Develop Authentify
Authentify is an authentication application that allows users to register, login, view their profile details, and log out. 
* Registration Screen:
  - Collect the user's name, email, password, address, date of birth (DOB), blood group, gender, etc.
  - Implement validation for email and password fields.
  - Save user details in the local database.
  - After registering, show a login form
* Login Form:
  - Allow users to log in using their registered email and password.
  - Validate email input.
  - Notify users to do registration if the email is not registered.
    - Take email and password
    - Check whether the user is available or not. If the user does not exist, notify the user to do registration.
    - Add validation for email.
* Home Screen:
  - Display user details retrieved from the local database upon successful login.
  - Include options in the toolbar for logout and deleting the user's account.
  - Maintain user session persistently until logout.
* Use `flutter_bloc` for state management.
* Write unit test for Bloc.


### Practical 20
#### Implement offline-first StoreMate product application
* GET API - https://fakestoreapi.com/products
* On the Home screen
  - Retrieve the list of products from an API and display it to the user using Listview.
  - Show product name, image, and button to favorite/unfavourite product.
* Allow the user to view the product by clicking on it. 
  - Show all details of the product.
  - Add an option to favorite/unfavourite the product.
* Add an option on the home screen to view favorite products
  - Show all favorite products.
  - Add option to remove from favorites.
  - Add option to remove all favorite item
  - Users can select multiple items with a long click and can remove all selected products from their favorites.
* The application should have offline functionality, allowing the user to continue browsing products even when they do not have an internet connection.
* The product data should be first fetched from the local database and then synced with remote API data.
* Add swipe-to-delete functionality to remove products from local storage.
* Add swipe-to-refresh functionality to refresh the local database with remote data.
* You can use any state management library.
* Add unit test.

# Streams

### Practical 21
#### Implement count-down timer application using Stream
* Build an app using one Screen
* On the Home screen
  - Add text fields to take user input for hours, minutes, and seconds.
  - Button to start/stop the timer.
  - Show remaining & elapsed time.
* The user should be able to set the duration of the timer and start it. 
* When the timer ends, the app should display a notification to indicate that the time is up.
* Also play sound and vibrate the device on the timer completes.
* Write Unit test.

### Practical 22
#### Implement a VocabVault app
* Allow users to search for the definition of any word in the English language.
* On the Home screen
  - Users should be able to search for a word by typing it into a search bar.
  - The app should display a list of words as the user types in the search view.
  - The app should display the word's definition along with pronunciations, parts of speech, examples, and synonyms.
  - Add an option to play pronunciations of words.
* Make sure the app will not make unnecessary API calls while typing in the search view.
* Use Streambuilder to render UI.
* API - https://api.dictionaryapi.dev/api/v2/entries/en/$word
* Write Unit test for viewModel.
    
# FireStore Database

### Practical 23
#### Develop EmployeeHub application
* Build an app using Google-sign-in
* The application should have a main entry point- Sign-in Screen
* On the Sign-in screen
- This should Display Image, introduction content, and **Sign in with Google** Button.
- On the Click of a button, authenticate a user with Google and Firebase authentication.
- After successful sign-in, navigate the user to the home screen.
* The application should display a list of employees on the home screen.
  - Show basic details including their name and job title. 
* When a user clicks on an employee from the list, the application should display their full details.
  - including their contact information, job title, and other important information. 
* The user should be able to add new employees to the directory by entering their basic information and saving it locally. 
  - Save employee name, email, contact info, job title, address, DOB, blood group, etc.
* Additionally, the user should be able to update an employee's information by selecting them from the employee list and editing their details.
* Finally, an employee should be deleted by swiping to delete from the home screen.
* Use Firestore to store data.
* Once the user signs in successfully, then redirect the user to the home screen without asking for authentication.
    
### Practical 24
#### Create a Contact Keeper application.
* On the Home screen,
  - Show all Contacts on the home screen.
    - Show name, phone number, and profile.
    - On click of contact show the contact profile.
  - Add an option to update contact details.
  - Add an option to delete a user by swiping to delete.
  - Add option to add contact with person name, multiple phone numbers, profile image, blood group, and address.
* Add a screen to edit/show contact details.
  - Add option to delete contact.
* The app should also update contacts in real-time, so changes made by one user are reflected across all devices.
* Use Firestore to store contact details.
* Use rx_dart for state management.
* Write Unit test.

### Practical 25
#### Create a Global News Tracker application.
* The Home screen UI
 - Design a home screen to display news articles.
   - Pagination
     - Fetch and display news articles in batches of 10.
     - Implement infinite scrolling to load more articles as the user scrolls.
   - Implement Search Functionality:
     -  Add a search bar at the top of the screen.
     -  Implement a search feature that filters the list of news articles based on user input.
     -  Update the UI dynamically as the user types in the search bar.
  - Sorting Functionality:
     - Add a sort button next to the search bar that triggers a pop-up for sorting options.
     - Implement sorting by popularity, date range (from date, to date), and publication date.
     - Fetch sorted data from the API based on the selected sorting option.
- Allow Advanced Filters
- Add options for users to filter news by Categories, Country, and Language
  -  Possible options by this API:
    - Categories: business, entertainment, general, health, science, sports, technology. Default: all categories.
    - Languages: ar, de, en, es, fr, he, it, nl, no, pt, ru, sv, ud, zh. Default: all languages.
    - country: ae, ar, at, au, be, bg, be, ca, ch, cn, co, cu, cz, de, eg, fr, gb, gr, hk, hu, id, ie, il, in, it, jp, kr, lt, lv, ma, mx, my, ng, nl, no, nz, ph, pl, pt, to, rs, ru, as, se, sg, si, sk, the, tr, tw, ua, us, ve, za. Default: all 
             countries.
- Detail screen:
  - Navigate to a detailed news screen upon tapping a news item.
  - Display the full news article with all the details.
- Support multiple languages and display news content based on the user's locale.
- Use MVVM architecture
- News API: GET `https://newsapi.org/v2/`
- generate API key from [here](https://newsapi.org/)






