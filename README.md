# Video-Game-Archive
This database aims to create a list of existing video games since its origin. While this is not an exhaustive list, the goal is to provide many titles from mainstream consoles, PC and some mobile games with an array of genre and series. 

If you are interested in contributing to this archive please follow the instructions below.

Before getting started, you must first have Git installed. if you do not have Git installed [Install it here](https://help.github.com/articles/set-up-git/).

The archive is broken down into several sections. What information this list needs from each title includes:

   -Title of the game

   -Developer of the game

   -Publisher of the game

   -The Series the game is from (if the games or characters exist in a franchise/series)

   -The release year of the game (North America date only)
   
   -The genre of the game

   -The mode of play the game has (single player, multi player, etc...).


## Fork this repository

Fork this repository by clicking on the fork button on the top of this page. The repository will now be on your Github account.

<img src="Video Game archive guide/Fork Repo.png">

## Clone this repository

Clone the forked repository. click on the code button and then click copy to clipboard icon.

<img src="Video Game archive guide/copy code repo.png">

Open the terminal and run the command:

```
Git clone "URL copied"
```

replace "URL copied" with the url that you actually copied (no quotation marks) and press enter.

## Create a branch

Change the directory on your terminal to the repository you cloned:

```
cd video-game-archive
```

Create a branch using the `git checkout` command:

```
git checkout -b branch-name
```

`branch-name` does not have to be the actual name of the branch you are creating. It is recommended to change it to something to let the creator know you are updating the archive.

## Make changes to your repository

the repository will now be cloned to your local machine. once you have cloned the repository, open the file `Video-Game-Archive` in the text editor you will be using to contribute to the archive (excel is the most recommended editor).

Fill in all parts of the database with each new title that you add.

DO NOT add titles that already exist in the database. you can find out if a title you are trying to add already exist by using CTRL + F and typing in the name of the title to see if it already exists in the archive.

You may fill in gaps you see in other entries.

Once you have finished with your contribution, save the file.

You can see the changes you made by using the terminal to run the command `Git status`.

Now add the changes you made by running the command:

```
git add Video-Game-Archive
```

Now commit the changes you made by running the following command:

```
git commit -m "your comment here"
```

provide any comment you want towards your contribution about what you did.

## Push your repository

Push your changes using the following command:

```
git push origin <branch-name>
```

The `branch-name` will be the name of the branch you created earlier.

## Submit your pull request

go back to the repository on your github account which should now reflect the changes you have just made. you will see a "compare and pull request" button. click the button.

<img src="Video Game archive guide/pull request repo.png">



Submit the pull request.

<img src="Video Game archive guide/create pull request repo.png">

Changes will be approved after further review.

Thanks for the contribution! any questions can be sent to mitchell.edwards3434@gmail.com
