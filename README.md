# Pokemon Yelp

## Overview

This is an app I worked on with other members of General Assembly for a group project. It is our take on what Pokemon Go should have been. In this App, you use the search function to find businesses using the Yelp API. When you select an individual store, you are given the ability to "scan" for a pokemon. When the pokemon appears at the store, it will remain there for an entire day (or 30 minutes in this test version). The user will need to physically go to the store, or very near it, to be able to capture the pokemon.

## Screenshots

<p align="left">
<img src="images/final search.jpg" height="300px" /> <img src="images/final detail1.jpg" height="300px" /> <img src="images/final-detail3.jpg" height="300px" /> 
</p>

<p align="left">
<img src="images/final capture.jpg" height="300px" /> <img src="images/final-pokedex" height="300px" />
</p>

## App features

- The app works very similar to Amazon. (I copied a lot of elements from the Amazon UI)
- User can view items in the store.
- Add items to cart, delete items in cart or checkout
- Search for items by name and type
- See and read comments and ratings left by others
- Write his/her comments.

## Programming structure

- The app relies very heavily on databases
- There are three main database "weapons", "weapon_types" and "elements" that supply the "store" with the items it needs
- The databases are connected by foreign keys
- This app uses activities mostly with animations turned off to accomadate a professional "store" app, and allows it to run smoothly

## Copyright issues

- Most of the item pictures for this app was taken off the internet.
- I copied the aethetic and UI of the amazon app and website. I did NOT copy any of their images, but made my own logo.

## Future plans

- I will be making the "Game" aspect of the app
- That aspect WILL have a lot more animations and cool stuff
- I will be migrating the database to the cloud, or maybe use an API of some sort to get a list of weapons
- As weapon lists grow, I will be implementing a filter function

## Known issues

- Picasso reloads everytime the recyclerview adds or deletes views. I need to add some logic to prevent this
- In the item detail view, the selection boxes look different depending on the version of Android. 
