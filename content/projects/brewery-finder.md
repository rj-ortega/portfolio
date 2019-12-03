+++
date = "2019-06-21"
title = "Brewery Finder"
math = "true"
+++

CLI app for finding breweries based on location and user criteria. Collaborated with Devin - [@darnold001](https://github.com/darnold001) on this project.

### > Installation

1. Clone our repo into the directory where you want the app
2. If you have bundler, run a ```bundle install``` in the root folder of the app to instal images/projects
3. Open up terminal and run the environment running ```ruby config/environment.rb```
4. Have fun!

###### if you don't have bundler or ruby, get it here! [Link to Bundler!](https://bundler.io/), [Link to Ruby!](https://www.ruby-lang.org/en/downloads/)

### > Demo

##### Welcome Menu
* Create user or hit database for existing user


![Welcome Menu](/images/projects/welcome_menu.png)

##### User Menu
* Access to Favorites menu
* Ability to look up brewery by city or name


![User Menu](/images/projects/user_menu.png)

##### Favorite menu
* Ability to see favorite breweries
* Lets you query API for up to date information on brewery
* Allows you to delete a brewery from database linked to current user
* Allows you to delete ALL breweries from both:
    * the database linked to the user
    * the associated brewery table


![Favorites Menu](/images/projects/favorites_menu.png)

##### API Brewery Query
* Built method to accept user input and query API for information using either:
    * City
    * Name of brewery
* After query user is prompted with the choice to save to favorites list


![Brewery Query](/images/projects/API_brewery_query.png)
![Add To Favorites Prompt](/images/projects/add_to_favorites.png)


### > Links

- [This project's github repo](https://github.com/rj-ortega/brewery-finder)

### > Model

```
    | User |>----------| Favorite Brewery |----------<| Brewery |
```

### > Technologies

- [Ruby](https://www.ruby-lang.org/en/) - High-level language
- [Sqlite3](https://www.sqlite.org/index.html) - open-source relational database management system
- [Open Brewery DB](https://www.openbrewerydb.org) - API for brewery information

MIT License