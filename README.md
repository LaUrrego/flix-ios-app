# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="https://github.com/LaUrrego/flix-ios-app/blob/main/GIF/updated-part2.gif"><br>

### Notes
Updating to add a tab bar with a "filtered" group of results proved to be more straightforward than expected, further expanding my working knowledge of how to work with APIs . The idea of having separate navigation controllers to retain a "dedicated history" helped drive home the importance of user experience. Learning to implement the new WKWebView will take some time, but will be an upcoming addition as well as a search bar results view. 

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

### App Walkthrough GIF
***iPhone 13 Pro Max + iPhone 8 Pro + iPod Touch Gen 7 Screens: ***

<img src="https://github.com/LaUrrego/flix-ios-app/blob/main/GIF/ezgif.com-gif-maker.gif">



### Notes
TableView was a complex topic to implement, but highly valuable once I saw how widespread it's applications were. It took several tries to understand auto layout and making it work with various screens, but the end result gave me perspective on how to hold myself accountable to making apps that were accessible by practically any iOS device, and not just the latest model. 

I was able to get the app to work on my phyical phone after connecting it with Xcode, but when I updated to iOS 16, compatibility was no longer supported so that I could add it as part of my walkthrough GIF. I will update it once Xcode catches up with support for iOS 16.
