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
#### Implement user profile UI
* Display a user's profile picture, name, and bio. 
* Here's [UI for reference](https://cdn.dribbble.com/userupload/5207044/file/original-ceb3338a4a693f6ab102298dd3745716.jpg?compress=1&resize=1024x768).

### Practical 2
#### Design a fitness app
* Create a Flutter application and Design [Static UI](https://dribbble.com/shots/21236904-Fitness-App-Design).
* The app should be responsive to different resolutions.
* Use Flutter's Materials Design 3 to enhance your design process.

### Practical 3
#### Develop a News application
* The home screen should show the toolbar, floating button, and news content.
* The toolbar on the screen should initially display the app's logo and title.
* As the user scrolls down to read the news, the toolbar should collapse to provide more space for the content.
  - You can use any dummy text/images as article content.
* Also animate the floating button as a user scrolls down, something like [this](https://dribbble.com/shots/3541588-Play-Button-Microinteraction)
* When the user reaches the end of the news and reverses scrolls, the toolbar should re-expand and display the app's logo & title.
* You can use any images or placeholder for eye-catching UI.
* Here's [UI for reference](https://cdn.dribbble.com/users/663782/screenshots/3742414/media/67464fde751beb373b4c6fa962edf718.gif).

### Practical 4
#### Implement Survey application
* On the Home screen, display a survey form.
  The survey form should show a question, 4 options, and a button for the next question.
  - Show progress as the user answers the question.
* Once the survey is completed, show a pop-up message thanking the user.
  - Use the Alert dialog to thank the user.
  - Dialog will have UI to show a thanks message, image, and button to complete the survey.
* Ask at least 3 questions with 4 options each. 
* The app should ask users about the Shopping experience. 
* Use a `PageView` to display questions.
* You can use any images or placeholder for eye-catching UI.
* Here's [UI for reference](https://cubicleninjas.com/wp-content/uploads/2021/01/NA-2021-Web-Questionnaire-3.jpg)

### Practical 5
#### Fitness Journal
* Develop an app for users to track their fitness activities.
* Use TextFields for users to input details for workout type, duration, date, and notes.
* Show all workout entries on the home screen.
* Add option to filter workout entries by date, type, duration 
* Ensure that the app maintains entered fitness data even after device rotation.

# Navigation and Routing

### Practical 6
#### Implement LeaveTracker App 
* Implement an app with two screens: Home and Apply-Leave Screens.
* On the Home screen, Implement UI same as Reference.
  - Use a dummy image for the person.
  - Add a Floating Action Button on the screen.
  -  On tap of the Floating action button, redirect the user to the Apply-Leave Screen.
* On the Apply-Leave screen,
  - It should contain `TextField` for user input.
  - Add `TextField` so user can enter the start date, end date, and reason for the leave.
  - Add a button to Apply for leave and the User should navigate back to the home screen by tapping the button.
* Show Applied leave on the home screen. 
  * The app should be responsive to different resolutions.
* You can use dummy data and any images to make UI eye-catchy.
* The app should follow material guidelines.
* Here's [UI for reference](https://github.com/canopas/flutter-developer-roadmap-2023/files/11687291/leaveTracher_ui.zip).


### Practical 7
#### Implement Navigation for a Messaging application
* Implement an app using 3 Screens - Onboard, sign-in, and Home.
* On the onboard screen, show a brief introduction to the app's features, such as messaging, voice and video calls, and file sharing.
  - Show images, titles, and subtitles to introduce app functionality.
  - Add a button to check the next/previous features. Also, the skip button to skip the onboarding flow.
* On the sign-in screen, allow the user to enter their email and password, and add validation to ensure the user enters a valid email address and password.
  - Use a dummy email/password to verify user input.
* After a successful login, the user should be redirected to the Home screen.
* On the Home screen, show a screen with three tabs in the persistent bottom navigation bar.
  - Implement screens for each tab
  - You can add any eye-catching UI. 
  - The user should not be able to go back to the login screen once redirected to the Home screen(After successful login).
* The app should be responsive to different resolutions.
* You can use any images or placeholder for eye-catching UI.
* Use [go_router](https://pub.dev/packages/go_router) for Navigation.
* Here's [UI for reference](https://www.uplabs.com/posts/message-app-ui-design-d614a2fa-5f98-486d-a296-d20c1dce64f1).


### Practical 8
#### Implement Color Pallate App for the web.
* Implement an app using the Bottom navigation bar with Two tabs: Home and Palette.
* On the Home screen,
  - Displays a list containing list tiles, each indicating a number in ascending order up to 100.
  - Each tile should be tappable and the User should navigate to Its detail screen.
  * On the detail screen
    - Show a number of list tile that the user selects.
  - The user should be able to redirect to the Detail screen by passing the number in the web URL.
* On the Palette screen,
  - Display a GridList of multiple color palettes.
  - By Clicking on the palate, the User should navigate to the Palette detail screen
  * On the palette Detail screen,
      - Show a Container with a particular color and add a button to favorite/unfavorite it.
* Use Navigator 2.0 for navigation.
* You can use any colors to make UI eye-catchy.
* Here's [UI for Reference](https://www.pinterest.com/pin/844706473831200541).

# Networking 

### Practical 9
#### Implement OnlineUserDirectory
* The app will have two screens
  - The home screen should show a list of users, retrieved from API.
  - Use Listview to show all users.
  - Add drag and drop support.
  - Show a summary of users in the list including name, image, and email.
  - GET Api Url : http://jsonplaceholder.typicode.com/users
* On the user-item click, display all details of the user on the next screen. 
  - Use GridView to show albums.
  - Show placeholder images for an album to make UI eye-catching.
  - GET Api Url : https://jsonplaceholder.typicode.com/albums?userId=1
* Use `http` for networking.

### Practical 10
#### Develop RecipeLister application
* Implement an app with two Screens - Home & Detail.
* On the Home Screen, display the list of recipes.
  - Each list item should show the recipe name and a short description.
  - Tapping a recipe should open the Recipe Detail Screen.
* On the Detail Screen show full recipe detail with recipe image and description.
  - Add a back button to navigate back to the list of recipes.
*  GET Api Url:  https://yummly2.p.rapidapi.com/feeds/list
*  To access API, log in or create an account to obtain an API key.
* Use `dio` for networking.

### Practical 11
#### Develop ImageSaver application
* Allow users to download an image from a given URL, display the image on the screen, and store the downloaded image file in the device's internal storage. 
* The app will have a one-screen.
  - Screen will have one Text field to enter the URL.
  - Buttons to download images and cancel downloads.
  - Show download progress in the progress bar.
  - Show download progress in the notification.
  - Show the downloaded image on full screen, once the download succeeds.
  - Add a button to save downloaded images in Gallery.
* Use `dio` for networking

### Practical 12
#### Implement Drink Explorer
* Allow users to search for their favourite mocktail detail.
* The app will have one Screen.
  - Add a search bar that allows users to search for mocktails by name
  - GET Api Url : https://www.thecocktaildb.com/api/json/v1/1/search.php?s={mocktail}
  - Default search text should be `mocktail`. That means initially showing `Mocktail` in the search bar and fetching `mocktail` using API from search text.
* When the user taps on a mocktail, the application should display the ingredients and details of the mocktail. 
  - Use dummy data if required.

 # State Management

### Practical 13
#### Implement MovieDirectory Application
* The app should have a Persistent bottom navigation bar with two tabs: Home and Favorite.
* On the Home screen, 
  - Show a List of movies in GridView.
  - Show movie poster image in the list including the name.
  - Get Api url: (https://netflix54.p.rapidapi.com)
  - On tap of the movie, display all details of the movie on the next screen with the favourite button.
* On the Favorite screen,
  - Show a list of favourite movies and a button to remove them from favourites.
*  Use Provider for State Management and go_router for navigation.

### Practical 14
#### Implement University directory application
* Allow users to browse and search universities from all around the world.
* On the Home screen,
  - Add a dropdown to select the country.
  - When a country is selected, display a list of universities located in that country from API.
* GET Request API - http://universities.hipolabs.com/search?country={country name}
* Use flutter_bloc for state management.

### Practical 15
#### Develop a Travel application
* Implement the app with three screens.
* The home screen should have a bottom bar with 3 tabs: Destinations, Search, and Settings. 
* The Destinations tab should display a list of popular travel destinations with images and descriptions. 
* The Search tab should Allow the user to search for destinations.
  - Add a search view to search different destinations.
  - Show a message in TextView to notify the user when the searched destination is not available.
  - Use dummy data for destinations.
* The Settings tab should allow the user to customize app settings.
  -  Add a toggle button for notification and day/night theme settings.
* App should preserve the state on tab change
  - If the user scrolls to the bottom of the destinations screen, it should preserve the scroll state across the tab change.
  - If a user searches for something on the search screen, the search result should be there when navigating to the search tab from other tabs.
  - If the user changes the setting's toggle, it should stay as it is when the user navigates between the tabs.
* Use riverpod for state management.


### Practical 16
#### Create My Journal application
* Enable users to Add their daily thoughts, feelings, experiences, and ideas. 
* The app will have a one-screen,
  - Show the user's thoughts in Grid.
  - Add TextField to take user input.
  - Add a button to save the user's thoughts.
  - Store inputs in the state Manager class as the state.
* The user should be able to add multiple thoughts.
* Use `riverpod` for state management.

### Practical 17
#### Develop MathQuest quiz application
* The app will have one quiz Screen
* The Home Screen is an entry point of the app.
  - This should provide an introduction to the quiz and a button to start the quiz. 
* The quiz should ask 10 questions, one at a time, and provide four answer options for each question. 
  - On click of the next button highlight the correct/wrong answer and show the next question.
  - Show progress as the user answers the questions.
* After the user answers all questions, the app should display a result view.
  - Which shows the number of correct answers and the total number of questions. 
  - Show the excellence level based on the score such as poor, good, and very good. 
  - Add a button to restart the quiz so that the user can play again.
* Implement day/night theme in the Quiz app.
* You can use any state management library for state management and image to build eye-catching UI.
* Use injectable and getIt for Dependency Injection.
* Here's [UI for reference](https://cdn.dribbble.com/users/2469034/screenshots/8210470/media/f02da6249ee8c25f187432c73d4eec27.png).
* Write unit test.

# Local Storage

### Practical 18
#### Develop Protasker application
* The App will have Three screens: Login, Home, and Detail screens
* On the Home screen,
  - Show a list of tasks with subtasks and time of creation.
  - Screen should have a Fab button to add a new task. 
  - Add a button on the cell, so the user can mark it as complete/incomplete.
  - On the cell swipe, show the delete option and allow the user to delete it by clicking on it.
  - On the appbar, display a summary of the number of tasks that are pending.
  - On click of the cell, redirect to the Task detail screen.
* On Detail screen,
  - Allow the user to edit this task and subtask.
  - Add a button to save the updated data.
* Use sq_lite to store data
* Display data from SQLite on the home screen.
* You can use any state management library.

### Practical 19
#### Develop Authentify
* An application that takes user credentials and basic information of a user and navigates to the home screen after a successful login.
* The app will have one screen
  - First, the app will show the register form
    - Take the user's name, email, and password for login
    - Other basic information such as an address, DOB, blood group, gender, etc.
    - Add validation for email and password.
    - Save user details in DataStore.
  - After registering, show a login form
    - Take email and password
    - Check whether the user is available or not. If the user does not exist, notify the user to do registration.
    - Add validation for email.
* Once the user logs in, the app should always show the home screen
  - It will show user details.
  - Add logout & delete user option in the toolbar.
  - Clear user session on logout.
  - Until the user logs out app should show the home screen.
  - When the user clicks the logout/delete user button, the app should clear/delete the user session and navigate back to the login screen.
  - Use `flutter_bloc` for state management.
  - Write unit test for Bloc.


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
* API - https://api.dictionaryapi.dev/api/v2/entries/en/<word>
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
* Build an app with one screen.
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

