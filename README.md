# coding-events-demo

Section 1: Purpose of the App
The purpose of this app is that people can use it to sign up for events they are interested in. Create/Delete Events in different categories. 
People should be able to follow types of events they are interested in through tags, and should be able to see the events they have already signed up for in a calendar. 
Within the calendar they should be able to add/drop/edit their current events, as well as any events they are responsible for hosting 

Section 2: Current State of the App
The current state of the app is that someone can add an event with description, location and category types, as well as add tags. 
Their is currently no specific user experience or a way for someone to follow specific tags

Section 3: Future Improvements 
The person class would need to be created. A person class would need to include a username, password so someone could login. 
It should also include an array list of events they are signed up for.
It should include an array list of tags they are following. 
Additionally you will need to be able to manipulate the items within this class. You will want to be able to get and set the list of events and tags. 
You will also want to add a method to delete events and tags from their calendar. 
From the controller you will want to display the list of events in a calendar in conjuction with a personal html user page. 

You may need to add an authentication class? Not sure about this piece for the login. 

There are many persons to one event. One person can attend many events as well. So it is a many-many relationship.
One person can follow many tags. A tag can be followed by many people. So it is many-many relationship.
Consider similarly event categories.
