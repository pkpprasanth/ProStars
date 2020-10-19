![Image description](https://i1.faceprep.in/ProGrad/prograd-logo.png)

# ProGrad Lab | REACT - MASTER OF HOF

## Learning Goals

In this exercise, the goal is to apply various higher order functions in react:

- when and how to setup react in your application,
- learn map, filter and reduce

## Getting started

1. Fork this repo
2. Clone this repo

Whenever you create a first significant change, you should make your first commit.

3. Follow these [guidelines to add, commit and push changes](https://github.com/FACEPrep-ProGrad/general-guidelines-labs-project-builders.git).

In the end of this document, you will find guidelines on how to submit the exercise.

## Instructions

### Iteration 1 | Display 5 Contacts

Let's take a look at the starter code.

Inside `src` folder, we can find `contacts.json`, a JSON file with the producer's contacts. Import this file and **create an array of the 5 first contacts** to use as your initial state.

Display that array of 5 contacts in a `<table>` and display the `picture`, `name`, and `popularity` of each contact.

To import `contacts.json` in `App.js`, you can simply use:

```js
import contacts from './contacts.json'
```

At the end of this iteration, your application should look like this:

![Screenshot](https://i.imgur.com/fPuwZXv.png)


### Iteration 2 | Add New Random Contacts

In your application, create a "*Add Random Contact* button so that every time you click on this button it adds a new random actor.

First randomly select a contact from the larger `contacts` array. Then add that contact the array of 5 in your state. Don't forget to `setState()` to cause React to re-render the app.

At the end of this iteration, your website will probably look like this:

![Screenshot](https://i.imgur.com/GuNyYiU.png)


### Iteration 3 | Sort Contacts By Name And Popularity

The producer asked you to add two new buttons to help them to sort their contacts. When you click on one of the buttons it should **sort the table by `name`** (alphabetically) and when click the other it should **sort by `popularity`** (highest first).

Don't forget to `setState()` after you sort!

This is what you may have at the end of this iteration:

![Screenshot](https://i.imgur.com/vUDGZ7Y.png)


### Bonus | Remove Contacts

The producer also would like to remove some of their contacts. Implement a "*Delete*" button on each row of your `<table>` that will let the user remove the contact they clicked.

When they click, you should get the index of the array of that actor and use it to remove the contact from the array. Don't forget to `setState()` after you remove the contact!

At the end of this iteration, your web page may look like this after playing a little bit with the "*Delete*" buttons.

![Screenshot](https://i.imgur.com/N3K1K1k.png)




Happy coding! :heart:
