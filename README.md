# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).
---

## Flix Part 1
#### REQUIRED (10pts)
- [X] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [X] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [X] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [X] (1pt) Run your app on a real device.

### App Walkthrough GIF
<img src="https://github.com/akheel-s/flix-app/blob/master/demo.gif" width=250><br>

### Notes
Building the app was relatively easy I found the system for pulling images from the API a little unnecessary and tedious I was surprised that we need a third party package for that and couldn't do it by default.

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [X] (5pts) User can tap a cell to see more details about a particular movie.
- [X] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF
<img src="https://github.com/akheel-s/flix-app/blob/master/demo2.gif" width=250><br>

### Notes
I had an error related to the MovieGridCell. This was because I had set the posterView to a UIview instead of UIimageview. Figuring that out took a long time. I also had a hard time with getting the layout for the poster view to look right. 
