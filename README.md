# Android-Engineer-Exercise_Week-1

# Clone for Android Studio
Copy link: https://github.com/Kaleorrmons/Android-Engineer-Exercise_Week-1.git

In android studio 4.0, go to VCS (if you've added a GitHub plugin) then click on Get from Version Control, it will load a window where you'll paste in the link (URL).

# What this App Does

This application was made as a learning experience. It is a simple login - register - forgot password - welcome application that utilizes Firebase to auth and verify that the user's email/password are correct in order to login. 


# Overview- HomeScreen

This is an android application that opens a homescreen for Anime, The best anime around! This will provide a: 

Login button

Register button

Forgot password button

Along with these buttons, this homescreen will also allow the user to input their email and password and then verify that their email and password, which need to meet requirements, are already registered. 

If the email is not registered it will prompt the user to register. 

If the email is registered, but not verified when they try to login, then this application will send out a verification link to the user's email. 

Only after they are registered, and verified, will the application allow the user to login and advance to the next page. 

The background is a gradient color that will switch between three different colors. 

# Overview- Registration 

This section is authenticated by Firebase.

Provides a place to input: 

Full Name

Age

Email address

Password

Also provides a button to register the user once all of the above fields are properly filled out. 

# Overview- Forgot Password

When the user clicks the button to forgot password, that button will bring them to this page. The user will then be asked to provide their email, with a button that will send out an email to reset their password. 

# Overview- Welcome

This is the page the user is able to reach after completing the registration/login processes. Has the simple text "Welcome!" and a logout button. 
