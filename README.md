[![Build Status](https://travis-ci.org/weboxstudio/meteor-angular2-seed.svg?branch=master)](https://travis-ci.org/weboxstudio/meteor-angular2-seed)

# Meteor-Angular-2-seed
Just a Meteor + Angular 2 project seed.

## Starting a new project
* Create a new repo on bitbucket or github.
* Create a new project in codio by selecting the _WEBOXSTUDIO/Meteor + Angular 2_ starter pack.
* Change the repo reference in the file _.git/config_.
* Start a new meteor project with `meteor create new-project`
* Move the folder _new-project/.meteor_ to the root directory
* Remove the folder _new-project_
* Setup your local GIT configuration:
  
  ```
  git config --local user.email "youraddress@email.com"
  git config --local user.name "Your Name"
  ```
  
## Creating a new box based on an existing project
* Create a new project in codio by selecting the _WEBOXSTUDIO/Meteor_ stack.
* Add the existing repo reference by typing `git remote add git@REPOPROVIDER/REPOREFERENCE.git` in console.
* Setup your local GIT configuration:
  
  ```
  git config --local user.email "youraddress@email.com"
  git config --local user.name "Your Name"
  ```
  
  
## Production settings

### Heroku
https://github.com/jordansissel/heroku-buildpack-meteor

## Updating the stack in codio
* Update the packages in the box based on this repo in codio.
* Go to the _stacks_ section.
* Add a new version to the _WEBOXSTUDIO/Meteor_ stack.

## Updating the starter pack in codio
* Update the code in the box based on this repo in codio.
* Go to the _starter packs_ section.
* Edit the stack version of the _WEBOXSTUDIO/Meteor + Angular 2_ starter pack.
