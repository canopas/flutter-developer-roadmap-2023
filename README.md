<h1 align="center">Flutter Developer Roadmap 2023</h1>

![alt text](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/Flutter-developer-roadmap-header-image%20(1).jpeg)

The Flutter Developer Roadmap 2023 includes **Practical exercises** that cover all the essential concepts used in day-to-day development.
# Guidelines

- Before starting any practical it's important to conduct research and learn the necessary concepts.

- As you progress through the practical exercises, make sure to apply the new knowledge you've gained in subsequent exercises. Try to allocate maximum 5 days to each practical.

- To keep track of your progress and share your work with your team lead, create a repository on GitLab where you can upload your completed exercises for review.

- To stay organized and track your progress, create tickets on ClickUp for each practical exercise. Each ticket should include a detailed description of the exercise, as well as an estimate of story points.

- As you work on each practical exercise, move the corresponding ticket from the "To-Do" queue to the "Done" queue to keep track of your progress. This will help you stay focused and motivated as you work through the roadmap.

# Table of contents
* [Useful References](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#useful-references)
* [Material Component](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#material-component)
* [Navigation and Routing](https://github.com/canopas/flutter-developer-roadmap-2023/blob/main/README.md#navigation-and-routing)
* Networking()
* State management()
* Depenedency Injection()
* Local Storage()
* Stream()
* Firestore Database()


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
#### Implement user profile UI
* Display a user's profile picture, name, and bio. 
* Here's [UI for reference](https://cdn.dribbble.com/userupload/5207044/file/original-ceb3338a4a693f6ab102298dd3745716.jpg?compress=1&resize=1024x768)

### Practical 2
#### Design fitness app
* Create a Flutter application and Design [Static UI](https://dribbble.com/shots/21236904-Fitness-App-Design)
* App should responsive for different resolutions.
* Use Flutter's Materials design 3 to enhance your design process.

### Practical 3
#### Develop collapsing toolbar for the News application
* Home screen should show toolbar and news content
* The toolbar on screen should initially display the app's logo and title.
* As the user scrolls down to read news, the toolbar should collapse to provide more space for the content.
  - You can use any dummy text/images as article content.
* When the user reaches the end of the news and reverses scrolls, the toolbar should re-expand and display the app's logo & title.
* You can use any images or placeholder to make UI eyecatchy
* Here's [UI for reference](https://cdn.dribbble.com/users/663782/screenshots/3742414/media/67464fde751beb373b4c6fa962edf718.gif)

### Practical 4
#### Implement Survey application
* On the Home screen display a survey form
  - Survey form should show questions, 4 options and a button for next question.
  - Show progress as user answers the question
* Once the survey is completed, show a pop-up message thanking the user
  - Use the Alert dialog to thank the user.
  - Dialog will have UI to show a thanks message, image and button to complete survey.
* Asks at least 3 questions with 4 options each. 
* App should ask users about the shopping experience. 
* Use TabView to display questions.
* You can use any images or placeholder to make UI eye-catchy.
* Here's [UI for reference](https://cubicleninjas.com/wp-content/uploads/2021/01/NA-2021-Web-Questionnaire-3.jpg)

## Practical 5
#### Implement Note-taking application
* Single Screen app
  - Which allows the user to enter a note 
  - Use EditText to take input from the user.
  - Add a button to reset the note.
* The application should have the ability to maintain the state of the TextField field, even after the device is rotated or in background. 
* This means that when the user rotates the device, the TextField field should retain its previous contents, and the user should be able to continue editing the note without losing any data.

# Navigation and Routing

### Practical 6
#### Implement LeaveTracker App 
* Implement an app with two screens: Home and Apply leave
* On the Home screen, Implement UI same as Reference
  - Use dummy image for the person.
  - Add Floating Action Button on the screen.
  -  On tap of Floating action button, redirect user to Apply Leave Screen.
* On Apply leave screen,
  - It should contain Textfields for user input.
  - Add textfieds so user can enter start date, end date and reason for the leave
  - Add button for Apply leave and User should be navigate back to home screen by tapping button.
* Show Applied leave on home screen. 
  * App should responsive for different resolutions.
* You can use dummy data and any images to make UI eye-catchy.
* App should follow material guidelines.
* Here's [UI for refrence](https://github.com/canopas/flutter-developer-roadmap-2023/files/11687291/leaveTracher_ui.zip)


### Practical 7
#### Implement Navigation for a Messaging application
* Implement an app using 3 Screens - Onboard, signIn and Home.
* On the onboard screen, show brief introduction to the app's features, such as messaging, voice and video calls, and file sharing.
  - Show images, titles and subtitles to introduce app functionality.
  - Add a button to check the next/previous features. Also, the skip button to skip the onboarding flow.
* On the sign-in screen, allow the user to enter their email and password, and add validation to ensure the user enters a valid email address and password.
  - Use dummy email/password to verify user input.
* After a successful login, the user should be redirected to the Home screen.
* On the Home screen, show a screen with three tabs in persistant bottom navigation bar
  - Implement Three screen for each tab
  - You can add any eye catchy UI 
  - The user should not be able to go back to the login screen once redirected to the Home screen.
* App should responsive for different resolutions.
* You can use any images or placeholder to make UI eye-catchy.
* Use [go_router](https://pub.dev/packages/go_router) for Navigation.
* Here's [UI for refrence](https://www.uplabs.com/posts/message-app-ui-design-d614a2fa-5f98-486d-a296-d20c1dce64f1)


### Practical 8
#### Implement Color Pallate App for web.
* Implement an app using Bottom navigation bar with Two tabs: Home and Pallate
* On Home screen,
  - Displays a list containing list tiles, each indicating a number in ascending order up to 100.
  - Each tile should be tapable and User should be navigate to It's detail screen
  * On detail screen
    - Show a number of list tile that is selected by user.
  - User should be able to redirect to Detail screen by passing number in url of web
* On the Pallate screen,
  - Display a GridList of multiple color pallate
  - By Clicking on the pallate, User should be navigate to pallate detail screen
  * On pallate Detail screen,
      - Show a Container with particular color and add button to favotite/unfavorite it.
* Use Navigator 2.0 for navigation.
* You can use any colors to make UI eye-catchy
* Here's [UI for Reference](https://www.pinterest.com/pin/844706473831200541)

# Networking 

### Practical 9
#### Implement OnlineUserDirectory
* The app will have two screens
  - Main home screen should show list of users, retrieved from API.
  - Use Listview to show all users.
  - Show summary of user in the list including name, image and email
  - GET Api Url : http://jsonplaceholder.typicode.com/users
* On the user item click, display all details of user on the next screen. 
  - Use GridView to show albums
  - Show placeholder image for an album to make UI eye-catchy
  - GET Api Url : https://jsonplaceholder.typicode.com/albums?userId=1
* Use http for networking

### Practical 10
#### Develop RecipeLister application
* Implement  app with two Screens - Home & detail.
* On the Home Screen, display the list of recipes.
  - Each list item should show the recipe name and a short description.
  - Tapping a recipe should open Detail Screen.
* On the Detail Screen show full recipe detail with recipe image and description
  - Add a back button to navigate back to the list of recipes.
*  GET Api Url: https://spoonacular-recipe-food-nutrition-v1.p.rapidapi.com/recipes/479101/information
*  To access RapidAPI, log in or create an account to obtain an API key.
* Use Dio for networking

### Practical 11
#### Develop ImageSaver application
* Allow users to download an image from a given URL, display the image on the screen, and store the downloaded image file in the device's internal storage. 
* The app will have a one Screen
  - Screen will have one Text field to enter the URL
  - Buttons to download images and cancel downloads
  - Show download progress in the progress bar
  - Show download progress in the notification
  - Show the downloaded image on full screen, once the download succeed
  - Add a button to save downloaded images in Gallery.
* Use Retrofit for networking

### Practical 12
#### Implement Drink Explorer
* Allow users to search for their favourite mocktail detail.
* The app will have one Screen
  - Add a search bar that allows users to search for mocktails by name
  - GET Api Url : https://www.thecocktaildb.com/api/json/v1/1/search.php?i={mocktail}
  - Default search text should be `mocktail`. That means initially showing `Mocktail` in the search bar and fetching `mocktail` using API
* When the user taps on a mocktail, the application should display the ingredients and detail of mocktail. 
  - Use dummy data if required

 # State Management

### Practical 13
#### Implement MovieDirectory Application
* The app should have Persistant bottom navigationbar with two tabs: Home and favourite
* On home screen, 
  - Show a List of movies in GridView
  - Show movies poster image in the list including name 
  - Get Api url: (https://netflix54.p.rapidapi.com)
  - On tap of movie, display all details of movie on the next screen with favourite button.
* On the Favourite screen,
  - Show a list of movie that has been added as favourite and Add button to remove it from favourites.
*  Use Provider for State Management and go_router for navigation.

### Practical 14
#### Implement University directory application
* Allow users to browse and search universities from all around the world.
* On Home screen
  - Add a dropdown to select the country
  - When a country is selected, display a list of universities located in that country from API.
* GET Request API - http://universities.hipolabs.com/search?country={country name}
* Use flutter_bloc for state management.

### Practical 15
#### Develop a Travel application
* Implement the app with three screens.
* Home screen should have a bottom bar with 3 tabs: Destinations, Search, and Settings. 
* The Destinations tab should display a list of popular travel destinations with images and descriptions. 
* The Search tab should Allow the user to search for destinations
  - Add search view to search different destination
  - Show a message in TextView to notify the user when the searched destination is not available
  - Use dummy data for destinations
* The Settings tab should allow the user to customize app settings
  -  Add a toggle button for notification and day/night theme settings.
* App should preserve the state on tab change
  - If the user scrolled to the bottom of the destinations screen, it should preserve the scroll state across the tab change.
  - If a user searches for something on the search screen, the search result should be there when navigating to the search tab from other tabs.
  - If the user changed the setting's toggle, it should stay as it is when the user navigate between the tabs.
* Use riverpod for state management.

# Depenedency Injection

### Practical 16
#### Create My Journal application
* Enable users to Add their daily thoughts, feelings, experiences, and ideas. 
* The app will have a one Screen
  - Show user's thoughts in Grid
  - Add TextField to take user input
  - Add a button to save the user's thought
  - Store inputs in state Manager class as state
* User should be able to add multiple thoughts.
* The application should be able to persist data even when there is a configuration change, such as screen rotation.
* Use Redux for state management.

### Practical 17
#### Develop MathQuest quiz application
* The app will have one quiz Screen
* The home Sceen be an entry point of the app
  - This should provide an introduction to the quiz and a button to start the quiz. 
* The quiz should ask 10 questions, one at a time, and provide four answer options for each question. 
  - On click of the next button highlight the correct/wrong answer and show the next question
  - Show progress as the user answers the questions
* After the user answers all questions, the app should display a result view
  - Which shows the number of correct answers and the total number of questions. 
  - Show the excellence level based on the score such as poor, good and very good. 
  - Add a button to restart the quiz so that the user can play again.
* Implement  day/night theme in the Quiz app
* You can use any state management library for state management and image to build eye-catchy UI
* Use injectable and getIt for Dependency Injection
* Here's [UI for reference](https://cdn.dribbble.com/users/2469034/screenshots/8210470/media/f02da6249ee8c25f187432c73d4eec27.png)
* Write unit test.

# Local Storage

### Practical 18
#### Develop Protasker application
* The App will have Three screens: Login, home and detail screens
* On the Home screen,
  - Show a list of tasks with subtask and time of creation.
  - Screen should have a Fab button to add a new task. 
  - Add button on cell, so user can marked it as complete/incomplete.
  - On the cell swipe, show delete option and allow user to delete it on click of delete.
  - On the appbar, display a summary of the number of tasks that are pending.
  - On click of cell, redirect to Task detail screen.
* On Detail screen,
  - allow user to edit this task and subtask.
  - add button to save the updated data.
* Use sq_lite to store data
* Display data from SQLite on the home screen.
* You can use any state management library.

### Practical 19
#### Develop Authentify
* An application that takes user credentials and basic information of a user and navigates to the home screen after a successful login.
* The app will have one Screen
  - First, the app will show the register form
    - Take the user's name, email and password for login
    - Other basic information such as an address, DOB, blood group and gender etc.
    - Add validation for email and password
    - Save user detail in DataStore
  - After registering, show a login form
    - Take email and password
    - Check whether the user is available or not. If the user does not exist, notify user to do registration
    - Add validation for email
* Once the user logs in, the app should always show the home screen
  - It will show user details
  - Add logout & delete user option in the toolbar
  - Clear user session on logout
  - Until the user logs out app should show the home screen.
  - When the user clicks the logout/delete user button, the app should clear/delete the user session and navigate back to the login screen.
  - Use flutter_bloc for state management
  - write unit test for Bloc


### Practical 20
#### Implement offline-first StoreMate product application
* GET API - https://fakestoreapi.com/products
* On Home screen
  - Retrieve the list of products from an API and displays it to the user using Listview
  - Show product name, image and button to favourite/unfavourite product
* Allow the user to view the product by clicking on it. 
  - Show all detail of the product
  - Add option to favourite/unfavourite the product
* Add an option on the home screen to view favourite products
  - Show all favourite products
  - Add option to remove from favourite
  - Add option to remove all favourite item
  - Use can select multiple items with a long click and can remove all selected products from their favourite.
* The application should have offline functionality, allowing the user to continue browsing products even when they do not have an internet connection.
* The product data should be first fetched from the local database and then sync with remote API data.
* Add swipe-to-delete functionality to remove products from local storage
* Add swipe-to-refresh functionality to refresh the local database with remote data
* You can use any state management library
* Add unit test.

# Streams

### Practical 21
#### Implement count-down timer application using Stream
* Build app using one Screen
* On Home screen
  - Add text fields to take user input for hours, minutes and second
  - Button to start/stop the timer
  - Show remaining & elapsed time 
* The user should be able to set the duration of the timer and start it. 
* When the timer ends, the app should display a notification to indicate that the time is up.
* Also play sound and vibrate device on timer completes.
* Write Unit test.

### Practical 22
#### Implement a VocabVault app
* Allow users to search for the definition of any word in the English language.
* On the Home screen
  - Users should be able to search for a word by typing it into a search bar
  - App should display as user type in the search view
  - The app should display the word's definition along with pronunciations, parts of speech, examples, and synonyms.
  - Add option to play pronunciations of word.
* Make sure the app will not make unnecessary API calls while typing in search view.
* Use Streambuilder to render UI.
* API - https://api.dictionaryapi.dev/api/v2/entries/en/<word>
* Write Unit test for viewModel.
    
# FireStore Database

### Practical 23
#### Develop EmployeeHub application
* Build app using Google-sign-in
* The application shouls have main entry point- Sign-in Sceen
* On Sign-in screen
- This should Display Image,introduction content and **SIgn in with Google** Button.
- On Click of button, authenticate user with google and firebase authentication.
- After successful sign in, navigate user to home screen.
* The application should display a list of employees on the home screen 
  - Show basic details including their name and job title. 
* When a user clicks on an employee from the list, the application should display their full details
  - including their contact information, job title, and other important information. 
* The user should be able to add new employees to the directory by entering their basic information and saving it locally. 
  - Save employee name, email, contact info, job title, address, DOB and blood group etc.
* Additionally, the user should be able to update an employee's information by selecting them from the employee list and editing their details.
* Finally, an employee should be deleted by swiping to delete from the home screen
* Use Firestore to store data
* Once user sign in successfully, then redirect user to home screen without asking for authentication.
    
### Practical 24
#### Create a Contact Keeper application.
* Build an app with one screen.
* On the Home screen
  - Show all Contacts on the home screen
    - Show name, phone number and profile
    - On click of contact show the contact profile
  - Add option to update contact detail
  - Add an option to delete a user by swiping to delete
  - Add option to add contact with person name, multiple phone numbers, profile image, blood group and address
* Add screen to edit/show contact detail
  - Add option to delete contact
* The app should also update contacts in real-time, so changes made by one user are reflected across all devices.
* Use Firestore to store contact details.
* Use rx_dart for state management.
* Write Unit test.

