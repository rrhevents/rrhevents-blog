# Everything you want to know about Jackbox Games

If you are like me, you've spent a lot of time playing remote games with your friends and family. One of those popular games is the Jackbox Games. Those are great because only one person needs to have purchased the game, and the only thing you need to play the game is your phone / tablet or computer, in which everyone has access to.

From my perspective, it would be extremely fun to be able to customize these game for birthday parties, weddings, work, networking, etc... So for those who are interested, this is a guide of knowledge for anyone looking to venture in to trying this out.

## First Party Solution
I wanted to highlight that Jackbox Games does have a very easy way to customize questions built into two of their games, Quiplash 2 and Drawful 2. This is by far the best way to customize those games. For most other games, keep on reading.


## The Jackbox Code
The thing about the Jackbox Games is that almost all the metadata and assets live on the computer and not on some server. This makes it easy to make changes. The one thing that can't be changed is the rules of the games themselves. And customizations must live within those constraints.

For the first 2 party packs, the questions lived inside the assets.bin file . To package and repackaged, used the JBPP Question Editer project below. The rest of the packs have all the questions in the game folder themselves.

Since the only thing to edit is json, using a good IDE that lets you see the structure of the folder and edit the json files. I recommend Visual Studio Code.

The overall jist of how the json is structured, is that there is a main json that has the entire inventory of questions. And then there are subdirectory of folders labeled with the id of on the folder and the assets for that question in the folder.


## How to Run a Game Party
As far a running a game party, I've had success using the concept of Breakout Rooms, which can be found in Zoom and Teams. Here is an article the describes it best, https://medium.com/swlh/how-to-run-a-zoom-cocktail-party-and-have-better-classes-conferences-and-meetings-too-dc2c5b58f8be


## Creative Inspiration
Sometimes coming up with the content, you might need some inspiration. So I've included some places to visit.
Quiplash - https://www.reddit.com/r/cahideas/
You Don't Know Jack - https://www.usefultrivia.com/   (I like this because it gives explanations on the right answer, which helps in this type of game.)


## Still need to figure out.
As far as the images and animations, those are packaged in a flash format. It should be possible to unpackage add your custom image and repackage the flash asset.


## Resources
Below is a list of links that were extremely helpful in checking out.
- https://github.com/misc0110/JBPPDrawfulQuestionEditor
- https://github.com/VoidXH/Trivia-Murder-Party-Modder