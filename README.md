Football App

![Alt text](img/Screenshot_1.png?raw=true "Football App")
![Alt text](img/Screenshot_2.png?raw=true "Football App")
![Alt text](img/Screenshot_3.png?raw=true "Football App")

## Contributors

[Erik Svedenlund](https://www.linkedin.com/in/erik-svedenlund-b8829512a/)
[Christian Nylander](https://www.linkedin.com/in/christian-nylander-70082812a/)

## Description

A live score football app using the API from [football-data.org](http://www.football-data.org/index) to fetch
data about the fixtures and teams in Premier League. Also using [our own API](https://github.com/eriksvedenlund/teamData/blob/master/teams.json) to fetch additional data about the teams.

Sort the matches by day using [react-native-calendar-strip](https://github.com/BugiDev/react-native-calendar-strip) to see when the match is taking place, what teams are playing eachother and the current score. Press the information button to navigate to the about screen. Here you will find further information about the teams. Such as their emblem, what arena the match is taking place at and
the team coaches. We have also included the feature to see the match form of the teams, i.e if the four latest matches for each team ended in a draw, loss or win.
From this screen you can also navigate to the Premier League Table to see the current standing of the teams. How many games are played so far, draws, losses, wins and points.

## Technologies

React Native

### Components used

* [Scrollview](https://facebook.github.io/react-native/docs/scrollview.html)
* [View](https://facebook.github.io/react-native/docs/view.html)
* [Text](https://facebook.github.io/react-native/docs/text.html)
* [Image](https://facebook.github.io/react-native/docs/image.html)
* [Stacknavigator](https://reactnavigation.org/docs/intro/)
* [Activityindicator](https://facebook.github.io/react-native/docs/activityindicator.html)
* [react-native-button](https://js.coach/react-native/react-native-button?search=button)
* [Touchablehighlight](https://facebook.github.io/react-native/docs/touchablehighlight.html)
* [react-native-calendar-strip](https://github.com/BugiDev/react-native-calendar-strip)
* [moment.js](https://momentjs.com/)

## API

[Football-data.org](http://www.football-data.org/index)

The football-data API provides football data of all major european leagues in a machine-readable way. By data I mean fixtures, teams, players, results and more. All this information is provided via an easy-to-use RESTful API in JSON (only) representation.
The API is easy to use with logical endpoints that is all explained in the thorough documentation on the website.

The API is usable without a key, but it is easy to sign up for free to get a key and get added benefits. With the key you will increase the rate limit from 50 requests per day to 50 request per minute, you will also get CORS support to use the API directly from JS-Frameworks like Angular.js or the like. It also helps the developer of the API to get usage analytics.

## Suggestions for further development

Due to time constraints this is as far as we got with the project. But there is ofcourse more you could do to further develop it.

In our project we only show matches from the Premier League but it is possible to get data about other european leagues as well from the API. It is also possible to get data about the players in the teams and display it. For further use you could build your own API and show whatever data you would like.
We also talked about using some kind of betting API with the project. So you could see the odds of what team is favored to win. 


## Devices tested during development

* LG G3
* Motorola G4
* Nexus X5 (emulator)
