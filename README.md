# RGB Game
[Deployed Link](https://e-huynh.github.io/RGB_game/)

[Github Repo](https://github.com/E-Huynh/RGB_game)

## Contact

Erik.W.Huynh@Gmail.com

[LinkedIn](https://www.linkedin.com/in/erik-huynh-228321196/)

[Portfolio](https://e-huynh.github.io/updated_portfolio/)

## Project Description
Note taker is a handy app that allows a user to take, store, and delete notes on the the go. Easily allowing a user to track notes helps to keep organization and task management. Notes will be stored on the cloud for easy access from anywhere.
## Functionality
Users can enter a note title and text and clicking the save icon to store the note. The note can be view by clicking the note title on the left, or deleting the note by clicking the delete icon. After saving a note, a new note template will automatically populate or a user can select the new note icon.
## Instructions
  ### Create new note
  * Enter a note title and text
  * Click the save icon
  ### Delete note
  * Click on the delete icon next to the note
  ### View note
  * Click on any note to view it
## Techonologies
  * [Express](https://expressjs.com/)
  * [NPM File System](https://nodejs.org/api/fs.html)
  * [NPM Path](https://nodejs.org/docs/latest/api/path.html)
  * HTML
  * Bootstrap
  * CSS
  * Jquery
  * Ajax API Calls
## Known bugs
  * ~~The first note may not display when clicked.~~ Fixed in commit: 9b5c9475279163bc8e1b058be17bc5258c7c7ab4
## Challenges & Accomplishments
One of the major challenges of this application was determining how to handle the db.json file that stores the notes. I was inclined to keep the notes stored in the server.js file but thought that it would make more sense to keep it as a separate file for ease of reading. This meant that I needed to use FS to read and write to the db.json while using JSON.parse and JSON.stringify to maining proper types.
Another challenge I overcame was troubleshooting the CSS styles and Jquery for notes.html. These files did not appear to apply to the notes.html page. With the help of my peers, TAs and professor, we were able to track the error through the network tab of Chrome's inspector and determine it was not able to load these files. I resolved this by having express target and load these files explicitly.
## Images
![Functionality GIF](https://github.com/E-Huynh/note_taker/blob/master/Develop/public/assets/Images/Note%20Taker%20Gif.gif?raw=true)
