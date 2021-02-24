# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [X] (5pts) User can tap a cell to see more details about a particular movie.
- [X] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="http://g.recordit.co/W8siklOAuE.gif" width=250><br>

### Notes
As I mentioned, I'm new to Swift and xcode, so when they had displayed black screen, I don't know how to fix it until I realize I have to move the arrow to the tab bar controller in order to make it as the first screen to view. It took me an necessary hour to retry this over and over again. And also sometimes I had exception issues, but as I watched the tutorial video again, I realize I forgot to add the identifier of "MovieGridCell" too. The videos are very helpful and informative.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [X] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [X] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [X] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="http://g.recordit.co/wImSN9DjGm.gif" width=250><br>

### Notes
One of the challenges I had is that I'm new to Swift and using xcode, so I was confused when it showed up "Flixter_demo[73089:1494439] [] nw_protocol_get_quic_image_block_invoke dlopen libquic failed", but after checking online, I assume it's because I have deleted the original component(Imageview) after I found it is placed wrong in the wrong place. The whole process is confusing, so I spend at least 2 times to redo everything.
