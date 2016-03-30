# ImmE
An Android app that could act just like "you"

ImmE
Basic Ideas
	The main idea of this application is to assist your friends when you are no available. Some of the feature that this application will contain are:

1.	Main Purpose of the App:
    a.	Keep tracking what we do in life every single day. This will be an Android app that could keep tracking yourself every single day since we assigned to the app.
	
2.	Fun Features -- Additional Features:
    a.	Respond to pre-determinate questions that you have already set up to your friends
    b.	Help you make plans for the current day
    c.	Allows permitted friends to access certain files that you desire
    d.	The Bot ( Virtual Version of Me) could play a prank on me.
    i.	Telling some of my secrets to my friends. (If I allowed the bot to has access to those informations).
    ii.	A privacy feature will added so you can filter the people that can have access to this information.

3.	Frameworks and Technologies
    a.	Web server API: Spring MVC
    b.	Database: MySQL
    c.	ORM: Hibernate
    d.	Android: Android SDK
    e.	Design: Material Design (Google)
    f.	Chat-Bot: To be determinate


Database Layout

Tables:
	Users
		Id, first name, last name, username, password, email, joined, active	

	Bot
		Id, bot id,  owner: username, bot name, created

	Activities
        Id, activity name, question, 
		

