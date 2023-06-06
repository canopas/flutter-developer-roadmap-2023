<h1 align="center">Flutter Developer Roadmap 2023</h1>

![alt text](https://github.com/canopas/Flutter-developer-roadmap-2023/blob/main/Flutter-developer-roadmap-header-image.jpeg)

The Flutter Developer Roadmap 2023 includes **Practical exercises** that cover all the essential concepts used in day-to-day development.
# Guidelines

- Before starting any practical it's important to conduct research and learn the necessary concepts.

- As you progress through the practical exercises, make sure to apply the new knowledge you've gained in subsequent exercises. Try to allocate no more than 3-4 days to each practical.

- To keep track of your progress and share your work with your team lead, create a repository on GitLab where you can upload your completed exercises for review.

- To stay organized and track your progress, create tickets on ClickUp for each practical exercise. Each ticket should include a detailed description of the exercise, as well as an estimate of story points.

- As you work on each practical exercise, move the corresponding ticket from the "To-Do" queue to the "Done" queue to keep track of your progress. This will help you stay focused and motivated as you work through the roadmap.

# Table of contents
* Useful References
* Material Component
* Navigation and Routing
* Networking

## Useful References
The references provided are aimed at individuals who have no prior knowledge or experience in developing Flutter apps. They serve as a starting point for beginners in the field, providing basic knowledge that is necessary before diving into Flutter development. 
If you already have knowledge and experience in Flutter development, you may not need to refer to the provided resources. 
* [Set up Flutter Environment](https://docs.flutter.dev/get-started/install)
* [Dart Language](https://dart.dev/language)
* [Version control Guideline](https://github.com/canopas/flutter-developer-roadmap/blob/main/GitGuideline.md)
* [Layout in Flutter](https://docs.flutter.dev/ui/layout#1-select-a-layout-widget)
* [Stateful and Stateless widget](https://docs.flutter.dev/ui/interactive#stateful-and-stateless-widgets)
* [State management approaches in Flutter](https://docs.flutter.dev/data-and-backend/state-mgmt/options)


# Material Component

### Practical 1
#### Static UI
* Create a Flutter application and Design Static UI(https://dribbble.com/shots/21236904-Fitness-App-Design)
* Use Flutter's Materials design 3 to enhance your design process.

### Practical 2
#### Implement basic Navigation
* Implement an app using two Screens - Onboard and Home Screen
* On the onboard screen, Implement UI same as Reference 
  - User should be navigate to Home screen on Tap of button
* On the Home screen, Implement the UI same as Reference without bottom navigation bar.
  - Use dummy image for the persons.
  - Add Floating Action Button on the screen
* On tap of Floating action button, Open modal bottom sheet.
  - On the modal bottom sheet, Impleemnt UI same as Reference.
  - The user should be able to dismiss it by swiping down or on tap of close button
* App should responsive for different resolutions.
* You can use any images or placeholder to make UI eye-catchy
* App should follow material guidelines
* Here's [UI for refrence](https://dribbble.com/shots/19021013-Dayzer-Mobile-App-Design-iOS-Android-UX-UI-Designer)

### Practical 3
#### Develop collapsing toolbar for the News application
* Home screen should show toolbar and news content
* The toolbar on screen should initially display the app's logo and title.
* As the user scrolls down to read news, the toolbar should collapse to provide more space for the content.
  - You can use any dummy text/images as article content.
* When the user reaches the end of the news and reverses scrolls, the toolbar should re-expand and display the app's logo & title
* You can use any images or placeholder to make UI eyecatchy
* App should follow material guidelines
* Here's [UI for reference](https://cdn.dribbble.com/users/663782/screenshots/3742414/media/67464fde751beb373b4c6fa962edf718.gif)

### Practical 4
#### Implement Survey application
* On the Home screen display a survey form
  - Survey form should show questions, 4 options and a button for next question.
  - Show progress as user answers the question
* Once the survey is completed, show a pop-up message thanking the user
  - Use the Alert dialog to thank the user.
  - Dialog will have UI to show a thanks message, image and button to complete survey
* Asks at least 3 questions with 4 options each. 
* App should ask users about the shopping experience. 
* You can use any images or placeholder to make UI eye-catchy
* App should follow material guidelines
* Here's [UI for reference](https://cubicleninjas.com/wp-content/uploads/2021/01/NA-2021-Web-Questionnaire-3.jpg)

# Navigation and Routing

## Practical 5
#### Implement Navigation for a Messaging application
* Implement an app using 3 Screens - Onboard, signIn and Home Activity
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
  - Add toggle button on Home screen to change the day/night theme
* App should responsive for different resolutions.
* Add support for day/night theme.
* You can use any images or placeholder to make UI eye-catchy
* App should follow material guidelines
* Use go_router for Navigation
* Here's [UI for refrence](https://www.uplabs.com/posts/message-app-ui-design-d614a2fa-5f98-486d-a296-d20c1dce64f1)

## Practical 6
#### Implement Note-taking application
* Single Screen app
  - Which allows the user to enter a note 
  - Use EditText to take input from the user.
  - Add a button to reset the note.
* The application should have the ability to maintain the state of the TextField field, even after the device is rotated. 
* This means that when the user rotates the device, the TextField field should retain its previous contents, and the user should be able to continue editing the note without losing any data.

# Networking

## Practical 6
#### 
