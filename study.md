# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
  - http://imgur.com/WDNdpL4
  - http://imgur.com/xrMhCvr
-   The data structure you plan to use.
  - i think that I will use a list of arrays of the possible wins. If either x or o
  - makes the sequence of those arrays, then x or o will win. If neither players
  - make the arrays of wins, and the board is full, it is a scatch, so no one wins.
  -
-   How you will take the markup of the game board and represent it in JS
  - I would wrap the whole game-board, all 9 spots in a class, within the HTML.
  - Then I would plan on putting all of the individual 9 spots in id's of HTML.
  - link the class and the id's to the javascript. Possibly by abc for horizontal
  - 123 for vertical--so a1 through c3.
  - If an id gets clicked, then display the player on that id location.

-   How you plan to approach this project.
  -Follow my wireframes to write HTML and CSS. Get the basic layout working
    work on making it look better after it's working.
  commit as often as a new feature is working on GitHub.
  manage game logic code.
    write pseudo code first for game logic, then write javascript from looking at that.
  create a front end server for the project
  write jquery for user to interact with the game
    write the psuedo code for jquery, or at least plan it out first briefly,
    then write the JQuery.
  create the backend server.
  make requests with the server using curl to see if its working.
  once it is working, write the AJAX.
  create more features in the css to make it look more visually appealing with colors
  and fonts and font sizes.
    see if the layout can be displayed in a better way, visually/logically for the
    nav, player, game, and footer.
  Write a readme for the project to explain what it is and what it does in the
  GitHub repository.

-   4-8 user stories for your game project.
  as a user, I can play by myself, tic tac toe.
  as a user, I can play with a friend as well.
  as a user, I can win as x in tic tac toe.
  as a user, I can win as o in tic tac toe.
  as a user, I can lose to someone on either side.
  as a user, I can have a scratch--no one wins.
  as a user, I can reset the game after playing, no matter who won.
  as a user, I can sign in with an email and password and have that information
    saved for me.

-   How you plan to keep your code modular.
  - For a line of code accomplishing an event, keep that in events file.
  - for the application program interface, keep that in an api file.
  - for username and password login, keep that in a auth folder.
  - keep main html in index.html, other html pages in other spots if necessary.
  - keep main css in main.css, other css pages in other spots if necessary.
  - keep files smaller and named accordingly as to what they do.

-   What creative spin will you add to your project?
    - Once I get the game actually working, then I will work on the more creative
    - aspect of it. I would like to get a nice and clean design with colors in the
    - nav and footer to make a theme and work on the css to make it visually appealing
    - and looking clean.

-   How will you use version control to backup / track your project?
  - Upon each working new instance of code, I will add the file and commit it. Once
  - a feature is working, I should commit that feature immediately on Github.
  - Once a new feature is commmited, then continue working on a new feature until
  - the project is completed.

-   Do you plan to attempt any of the bonuses?
  - based on how I have been following the last classes on Thursday and friday,
  - which was hard for me to follow, I will just be trying to get the barebones done
  - first. If, and once, I have the main features completed and the game is working,
  - then I would try to work on the bonuses, but honestly don't know if I will get
  - that far the way things have been going.



You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur]
(http://imgur.com/).
