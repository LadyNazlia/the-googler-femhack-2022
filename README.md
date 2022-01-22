# the-googler-femhack-2022
This projeect is a prototype created for the individual front end challenge for FemHack 2022.


<strong>Special Note:</strong>


 Due to the limit of 16 hours to complete this prototype and my extremely limited experience with HTML and CSS, this is merely being completed for the sake professional experience that I can gain from challenging myself to learn something new in a short amount of time.



<strong>Challenge Requirements:</strong>


Marissa personally asked you to create the app prototype that allows their users to:

    Login and register (no persistence required)
    Take a new note that contains two kinds of text:
        Title
        Description
    Visualize the notes in a grid/list view
    Add tags to the notes
    Delete notes
    Edit notes
    

<!-----------------------------
Initial Planning:
------------------------------->

- Due to my lack of experience in app development, I have decided to make a browser based "app" that can ideally work easily as a browser based application with some future modifications.
- The "app" will start with a home screen where users can choose to log in or register.
- Based on user selection, they will either be taken to the login or registration page
- Once users have logged in, they will be brought to a dashboard of sorts where they can choose to create a new note, delete a note, or edit a note.
- Depending on the option selected will depend on what page they are taken to next.
- I'd like to have all notes present in a list, but I'm not sure that I know how to make that happen yet.
- For the sake of the prototype and the lack of JS functionality, I will have a few pre-made notes that users can see and interact with
- I don't know how to do tags yet, but I'll explore the MDN as time permits.


<!-----------------------------
Descriptions of Files included:
------------------------------->

- index.html - the main page of the app that greets users and asks whether they want to login or register
- stylesheet.css - contains all of the CSS content for the whole app
- login.html - once users select "login" from the homepage, they are taken to this app to log in
- register.html - for new users, once they select "register" on the homepage, they are take to this page to register
- notes.html - this is a sample of what a notes page would look like after the user adds note or this could be sample notes for new users
- edit.html - for the time being, this does not include any JS so this is what the page would look like when users choose "edit" from the notes.html page
- delete.html - for the time being, this file serves as an example of what it would look like if the user choose "delete" from the notes.html page
- create.html - for the time being, this files serves as an example of what it would look like if the user choose "create" from the notes.html page

<!-----------------------------
Future Improvements:
------------------------------->
- Add Javascript so that edit.html/delete.html/create.html pages can be removed and replaced with interactive JS content on the notes.html page instead
- Add a backend database that allows usernames and passwords to be installed
- Add password requirements and checks to make sure passwords match on the register.html page
- Add email/database functionality for password reset
- Add drag and move feature for notes on the note.html page
- Add custom tag creation option for when users create new notes
