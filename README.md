# MyBlog App
## Author
[Preston-Too](https://github.com/Preston-Too)

## Live Link
* [here] ()

## Description
 MyBlog is an application that is developed using flask. This is a personal blogging website where you can create and share your opinions and other users can read and comment on them. Also displays random quotes on the site.

## User Stories
What the user does...
* View the blog posts and random quotes on the site.
* Comment on blog posts.
* View the most recent posts.
* Get An email alert when a new post is made by joining a subscription.
The writer would like to... :
* sign in to the blog and see random quotes.
* create a blog from the application.
* delete comments that I find insulting or degrading.
* update or delete blogs I have created.

## Installation / Setup instruction

#### The application requires the following installations to operate 
* python3.6
* pip

#### Cloning

* Open Terminal {Ctrl+Alt+T}

* git clone ```https://github.com/Preston-Too/MyBlog-App.git```

* Move to the folder and install requirements
    ```pip install -r requirements.txt```

* Running the application
    ```python3.6 manage.py runserver / .start.sh```
* Testing the application
    ```python3.6 manage.py test```


## Behaviour Driven Development
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
|On loading view random quotes | Signup if no account|Taken to the clicked blog|
|Click on  New blog| If logged in, display form to add new blog| Redirected to the all blogs page and all blogs displayed|
|Click on Delete blog| Delete a blog|  Redirected to the all blogs page|
|Click add comment icon| Redirects to the comment page|Displays a comment form and display added comment|
|Click on profile |Redirects to the profile page|User adds bio and profile picture|
|Click on Sign Out|Redirects to the home page| Signs user out|


## Technologies Used

* python3.8
* Flask
* Bootstrap
* HTML / CSS

## Known Bugs
* There are no known bugs at the moment

## Contact Information 

If you have any question or contributions, please email me at [toopreston@gmail.com]

## License
* [[License: MIT]](LICENCE.md)
* Copyright (c) 2020 **Preston Too**