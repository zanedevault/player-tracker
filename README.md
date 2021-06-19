commit test 1

# Player Tracker

This is the project that I'm using to learn OOP, MVC, Test Driven Development, phpDocumentor, Composer and probably some JavaScript and maybe even a little React.

For the sake of full disclosure, this is the fourth time that I've started this repo from scratch.


## This WP plugin should:
- Choose from a list of Players to track from the user in WP admin
- Pull the per game stats for those players from API Sports
- Display the data where the user puts the shortcode


### Possible Enhancements (working list)
- Allow search and add of any player in API Sports
- Use a different API
- Allow user to choose what stats to display
- Add links to highlights
- Add links to match reports
- Add links to other articles mentioning the player (maybe the user can provide a list of sites to crawl for these links)


## Important Reminder
*I want to use OOP and MVC (Model, View, Controller) programming patterns as much as possible*


## To Do
1. Get MVP running
   1. Set up shortcode to rough display a hard coded table with hard coded stats
      * class player_data_display
   2. Set up a class that will hold the player data
      * class player_data
   3. Create hard coded objects from player_data that will populate the shortcode
   4. Set up class that will connect to the API Sports
      * class api_connection
   5. Set up class that will send a request to the API Sports
      * class api_request
   6. Set up class to will accept the response from the API Sports and format the data to work with player_data class
      * class api_return
   7. Set up class to hold the users choices for players
      * class users_players_list
   8. Set up class to allow user to populate users_players_list from WP Admin
      * class wp_admin_interaction
   9. Style out display with interactions
   10. Go through [WP Plugin Handbook](https://developer.wordpress.org/plugins/) and make sure that I implemented security and any other required / suggested features
2. Pick next enhancement and plan out


## Links
- [WP Plugin Handbook](https://developer.wordpress.org/plugins/)
- [API Sports](https://dashboard.api-football.com/)
- [Carl Alexander](https://carlalexander.ca/)
- [Tom McFarlin](https://tommcfarlin.com/)
- [Treehouse PHP OOP](https://teamtreehouse.com/library/topic:php/q:object-oriented)
- [GitHub Plugin Boilerplate](https://github.com/devinvinson/WordPress-Plugin-Boilerplate/)
- [Slushman Sample Boilerplate](https://github.com/slushman/now-hiring)
