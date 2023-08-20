# CS360-Repo

### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
  
  We developed an android weight tracking app that seeks to provide customers with an intuitive way for tracking their weight loss goals. Through tracking weight overtime and notifying the user when they meet their goals, users can stay motivated, inform and celebrate when they reach their goals. User has the capability to add their goal weight and their current weight. Every day, user can enter their weight and see how their weight has changed overtime. This is viewed from a grid. There is also the capability for the user to update the day, so if they made a mistake, or they reweighed for that day, it can be changed. Deleting a record is also possible in the application.
  
### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
This app features a login screen, and a screen for adding daily weight, goal weight, and make changes to previous entries. It was important that the user had clarity with what button interacted with each part. It was also important for the app to be ergonomic. To do this, we maintained a design where everything was clear in the app itself, and each component was clearly connected to each other. This was successful due to how intuitive the app was for users.
  
### How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
The first part that was designed was the model for how to store the data. SQLite was used to store passwords and usernames, as well as the daily weight data. From here, an implementation for the pieces to show up on the UI was developed. This made the process simple, as we had the foundations of the application built. This will be useful in the future, as this type of development makes scope clear and allows you to think about the data layer before the UI interactions.

### How did you test to ensure your code was functional? Why is this process important and what did it reveal?
It was primarily manually tested. This is important as users will interact with the app, and so we should understand how users might interact with the app and whawt bugs might come up during certain actions.

### Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
I innovated through the data layer. It was important to have a layer of security, so when developing the SQLite databases, I used 2 different tables. This way, many users can interact with the application, while also having a personalized experience.

### In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
I think the UI was particualary successful, as I was able to map update and delete by the entries shown. This was primarily challenging, but presents simplicity to the user, improving the overall experience.
