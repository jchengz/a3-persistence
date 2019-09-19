Readme
---
Justin Cheng
https://a3-jchengz.glitch.me/

## Your Web Application Title

Link: https://a3-jchengz.glitch.me/

Include a very brief summary of your project here. Images are encouraged, along with concise, high-level text. Be sure to include:

For A3- I decided to make a new web application. This one allows the user to enter quotes and the author of quotes. There is a max of 20 characters for the authors name and
a max of 800 character for the quote. To access the application, you must use the google log-in (yours, or slacked to the TAs). You will be able to view the quotes after logging in 
add your own quotes or edit any quotes. Shown in the table of quotes (See All Quotes) is the the author followed by the quote, followed by the number of words (wordcount) in the
quote. To "log out" close the window or hit the exit button.

The CSS framework used is Bootstrap 4, which was chosen based on its popularity and was suggested by multiple peers.

The most challenging part for me was setting up the google api login. I had to properly set up the clientID and do a lot of "outside the application" work to get the google
login to actually work. And then there was the issue of "logging out" which was solved using a few lines of code. The other issue is communication with the database and actually
making additions, edits, and removals to and from the database. 

- Express Middleware Summary:

1. body-parser: to make more efficient and easy the parsing of jsons
2. lowdb: database used for storing values (quotes, etc)
3. sessions: to enable and maintain user access
4. cors: to enable origin from all platforms
5. passport: used for authentification of user

## Technical Achievements
- **OAuth2 w/ Google Api**: I used OAuth authentication via Google strategy
- **Using Google Api**: Greets the used after pulling info based on google account login

### Design/Evaluation Achievements
- **Baseline User Input Checks**: Using alerts, this checks user inputs to make sure they are entering valid inputs (not extensive and expects "benign users") 
- **Single HTML File by Design**: The application functions using one html file that is the index.
- **CSS Modifications**: Bootstrap CSS modifications
: 
: 