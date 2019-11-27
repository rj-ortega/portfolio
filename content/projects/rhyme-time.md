+++
date = "2019-07-30"
title = "Rhyme Time"
math = "true"
+++

Ruby on Rails server rendered website to help users write rhyming poetry

Collaborated with Dustin Keys [@codeHustler91](https://github.com/codeHustler91) on the project

### > Demo
##### Welcome Menu
   - Login, Sign Up, and view all poems
   - Get inspired by a random Shakespeare Sonnet!
   - Visit the app github page and Flatiron School website through the links in the top right corner

   ![Welcome Menu](/images/projects/welcome.png)

##### Create User/Sign Up
   - Enter your Name, Username, and Password to securely login to your account
   - Enjoy the number of users statistic, you may want to divide by 1 million...
   
   ![Create User](/images/projects/create_user.png)

##### Login
   - Enter your existing username and password
   - Check out the most recent poem entered into our database

   ![Login](/images/projects/login.png)

##### Poem Index
   - See a list of all the poems created by our creative users!

   ![Poem Index](/images/projects/poem_index.png)

##### User Page
   - List of Words
       - Save all of your favorite words
       - Click add word 
       - See rhyming words
       - See adjectives for words
       - Delete your word
   - List of Poems
       - Click write your poem
       - Save all of your poems
       - Delete or edit your poems
   - Log out of your account
   - Delete your account
       - Don't leave us!

   ![User Page](/images/projects/user_page.png)

##### Write Poetry

- Title your poem
- Write your poem
- Use the favorite words list at the bottom of the page
      - See rhymes of favorite words and use them in your poem!
      - See adjectives for favorite words and use them in your poem!
- Click 'Create Poem' to save it to your profile
- Add more favorite words and then use the poem edit button to finish your masterpiece!

![Write Poetry](/images/projects/write_poetry.png)

### > Model
```
| Poem |>-----| UserPoems |-----<| User |>-----| UserWords |-----<| Words |
```

### > Links

- [Github Repo](https://github.com/rj-ortega/rhyme_time)
- [Deployment website](https://mysterious-tor-87367.herokuapp.com/users)

### > Technologies

   - [Ruby](https://www.ruby-lang.org/en/) - High-level language
   - [RoR](https://rubyonrails.org/) - Ruby on Rails API server
   - [Sass](https://sass-lang.com) - Style sheet language
   - [jQuery](https://jquery.com/) - JavaScript library  
   - [Sinatra](http://sinatrarb.com/) - DSL (Domain Specific Language)
   - [PostgreSQL](https://www.postgresql.org/) - open-source relational database management system
   - [Datamuse API](https://www.datamuse.com/api/)
   - [PoetryDB](http://poetrydb.org/index.html)

   MIT Licence