# Notes
An android application which will help you save notes for as long as you want.

##Layout 
The Layout of the app consists of a ListView which displays the saved note. The notes can be opened by tapping on that particular note item of the list view. 
A note can be deleted by long pressing the item of the list view.
A Menu Inflater has been included in the app layout which provide the "Add note " and "creators" tab .
A new note can be added by clicking on the "Add note" tab in the menu inflater.
"creators" tab in the menu inflater opens the developers window.

##Data Management
ArrayList Datastructure has been used in this app which is used to store the content of the notes. The ArrayList is then fixed into an arrayAdapter which is then set to the listView for displaying the content.
For permanent storage we have used "SharedPreferences" which helps to keep the data stored even if the app is shut down.  
