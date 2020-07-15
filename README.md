# Notes
An android application which will help you save notes for as long as you want.
![alt text](https://github.com/swayamkaul/Notes/blob/master/screenShots/Mainactivity.png)
## How to use
You may transfer the "NotesApp.apk" file to your android mobile mobile phone and install it.

## Layout 
The Layout of the app consists of a ListView which displays the saved note. The notes can be opened by tapping on that particular note item of the list view. 
A note can be deleted by long pressing the item of the list view.
![alt text](https://github.com/swayamkaul/Notes/blob/master/screenShots/deleteNote.png)
A Menu Inflater has been included in the app layout which provide the "Add note " and "creators" tab .
A new note can be added by clicking on the "Add note" tab in the menu inflater.
"creators" tab in the menu inflater opens the developers window.
![alt text](https://github.com/swayamkaul/Notes/blob/master/screenShots/MenuInflater.png)

## Data Management
ArrayList Datastructure has been used in this app which is used to store the content of the notes. The ArrayList is then put into an arrayAdapter which is then set to the listView for displaying the content.
![alt text](https://github.com/swayamkaul/Notes/blob/master/screenShots/code.png)
For permanent storage we have used "SharedPreferences" which helps to keep the data stored even if the app is shut down.  

## Developers
#### Moulik Bhardwaj 185506 
#### Swayam Kaul 185512 
#### Rishabh Dhenkawat 185519

