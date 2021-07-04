# Project-L : Shopping List Option

## Purpose

The purpose of this project is to build a simple webapp that provides users with an ability to keep track of a shopping list.


## Milestones or Required Features

* User Must be able to add an item to the shopping list
* User must be able to view their whole shopping list
* User must be able to delete an individual item from the shopping list
* User mus be able to delete their entire shopping list with a single button click (without individual item deletions)
* Each user must be able to login with their Google Account
* User's shopping list must persist between logins 


## Initial Obstacles or Considerations

- Programming Language, Frameworks, etc to use for implementation
- Visual Structure of App ( major factor in how app will be coded )
- Organization of ideas and plan of attack for implementation of various milestones
- Research into how to effectively use Google for Authentication of users 
- Best strategy for data persistence

  #### Early Stage Plan For Implementation
  
  1. Utilizing Javascript language (Node.js) for overall implementation of app
  2. Figma will be tool used to set up visual structure and organizational cues for app
     [Figma schematic link: https://www.figma.com/file/zlw55Qi2hqXK4qv37tws4E/Untitled?node-id=0%3A1]
  3. Trello Agile/Project board will document organization of tasks and features for overall project
     [Trello Link: https://trello.com/b/e6FkqfXa]
  4. Google, Firebase for database/user authentication
  
## References

  - Firebase: https://firebase.google.com/docs/reference
  - Node.js: https://nodejs.org/en/docs/guides/
  - Express: https://expressjs.com/en/starter/hello-world.html
  - Google App Engine: https://cloud.google.com/appengine/docs/standard


## Future Scope

This project was very interesting and opened my eyes to even more features and possibilities that can widen user audience and capabilities among other things.
Here are a few that I intend on adding to the project moving forward:

1. Allowing user to "check off" items from the shopping list to designate that they have been received or accounted for.
    *   This can be as simple as adding a button or check to the app that, when clicked, puts a ~~strikethrough~~ the words of the item
    *   Another implementation path could be to have the aforementioned button remove it from the overall list and add it to a separate "completed" list

2. User able to save multiple shopping lists and be able to access a particular one when needed
    * For example they can create a shopping list based on a recipe for a particular dish and save it as " Items for My Famous Peach Cobbler Recipe"
    * Most likely will need to utilize database to store data for each custom shopping list and items thereof
    * From a UI perspective, a dropdown menu can be added to user's page that houses the titles of each custom list, the populates the screen when selected
    * Even a step further, user can add image that populates a card. Cards can show on user's page upon login like a dashboard of sorts

3. User able to share shopping list with others
    * User can share the list via email or shareable link
    * Or (really way in the future scope) incorporate social media aspects in terms of being able to view lists from other users or following other list creators

