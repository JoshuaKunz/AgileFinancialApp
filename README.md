# Agile Team #2
Josh Kunz (Add your names here)
8/27/2020

# Budget and Financial Management Application

## Helpful Articles:
* [Android MVVM Design Pattern](https://www.journaldev.com/20292/android-mvvm-design-pattern)

### Requirements:
1. Users must have a secure login
2. Users should be able to keep track of deposits(income)
3. Users should be able to create budget categories and assign money to the category
4. Users should be able to create and track expenditures against a given category
5. Users should be able to see how much money remains in a category
6. The user interface should be clean and intuitive

### Technology:
1. Language: Java
2. IDE: Android Studio
3. Version Control: GIT, or any other version control app that works with GIT.

### Design Patterns:
1. Model View ViewModel (MVVM)
2. Factory

### Roles: 
TODO: Create roles.
Just to throw out some ideas
1. Front end
2. Back end
3. Database
4. Unit tests


## Things to download:
1. [GIT](https://git-scm.com/downloads)
2. [Source Tree](https://www.sourcetreeapp.com/) if you don’t plan on using the command line
3. [Android Studio](https://developer.android.com/studio)


Make sure you switch into the branch: develop because Master is for our working project updates. Before you start making changes, be sure to create a new branch with the naming convention <yourName/nameOfBranch>. For example I would do something like:

```
git checkout develop
git checkout -b JoshKunz/CreatingModels
```

To save your changes with a commit, simply use the command:

```
git commit -am “I created some new models”
```

And to push your changes to the GitHub repository you can use the commands:

```
git push
```

Note: if it’s your first time pushing to the new branch it will show a set-upstream command to use to create the upstream.
Later on when you are finished with your branch you can set up a pull request, where everyone can look at the code and review it. Once everyone gives the thumbs up I will merge it into develop, and everyone can pull your code into their local repository.

```
git checkout develop
git pull
```
You may need to stash your changes first before you can.

### Useful Git commands:
If you are not using the command line, you can skip this.
You can do a simple google search on these commands to get an idea of what they do. 
* git clone
* git checkout -b branchName 
NOTE: Using -b will create a new branch based off of the branch you're currently checked out, and checks you into the newly created branch.
* git pull
* git status
* git commit -am “your commit text here” ONLY commit to your own branches
* git push ONLY push commits to your own branches
* git merge ONLY merge into your own branches
As far as merging into develop or master, you will have to set up a pull request first.

### Android Studio Setup Guide:
Follow along the chat messages in Discord.


### Design Concepts(UI):
 



### Naming Conventions:
 



### Models:
* UserModel
* DepositModel
* CategoryModel

### ViewModels:
* OverviewViewModel

### Views:
* OverviewView

### Other Meaningful Classes:



### Database Schema:
TODO:Design the database relational model for this app.

### Testing Strategies:
* Create multiple environments and use dependency injection to set which environment to use throughout the application.
* Unit tests

