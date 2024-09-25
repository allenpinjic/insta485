<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
<h3 align="center">Instagram Clone (Server-Side)</h3>
  <p align="center">
    An Instagram clone implemented with server-side dynamic pages
  </p>
  <p align="center">
    EECS 485 - September 2024
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project
<p align="center">
  A multi-user, interactive clone of Instagram implemented with server-side dynamic pages that features the ability to create, update, and delete users, posts, comments, and likes
</p>

### Built With
[![C++][cplusplus]][cplusplus-url]
[![Xcode][xcode]][xcode-url]

<!-- FEATURES -->
## Features

- [ ] falsk application py virtual environment
- [ ] sql usage
- [ ] jinja2
- [ ] session cookies
- [ ] ec2 instance

## Description
This project imitates the same kinds of experiences found in the real Instagram appication (including most other social media applications as well), with a number of different pages that as a whole form a functioning and unified website experience.

## Website Pages

<p align="center"> 
  Each webpage has a unique set of features that fulfills a particular set of goals, similar to Instagram itself
</p>

### Index

<p align="center"> 
  Also called the <strong>Main Page</strong>, it displays all of the posts that exist within the SQL database at any given time along with information about the post itself (ie. the post's owner, their profile picture, etc.), comments, and the ability to delete one's own comments
</p>

### User Profile

<p align="center"> 
  Displays information specific to this given user (including the number of posts they have posted, the number of followers, etc.) Alongside this information, there is also links that deal with the user's account as well as all of the posts that the given user has previouly posted.
</p>

### Followers

<p align="center"> 
  Lists each person that is following a given user, including their username and profile picture, along with a button that allows the current logged-in user to follow/unfollow them
</p>

### Following

<p align="center"> 
  Lists each person that a given user is following, including their username and profile picture, along with a button that allows the current logged-in user to follow/unfollow them
</p>

### Post

<p align="center"> 
  Displays a given post and related information (ie. the post's owner, their profile picture, and the timestamp), its comments, as well as the ability to like/unlike the post and delete your own comment
</p>

### Explore

<p align="center"> 
  Displays users that you are not currently follows and allows you to follow/unfollow them respectively
</p>

### Login

<p align="center"> 
  Displays buttons that allow a user to login via their username and password
</p>

### Create

<p align="center"> 
  Allows for the creation of a new user with a specific username, password, and to upload a specific profile picture
</p>

### Delete

<p align="center"> 
  Allows the logged-in user to delete their own account, along with all information associated with them (any posts, comments, likes, and user information)
</p>

### Edit

<p align="center"> 
  Allows the user to change their account by uploading a new profile picture, changing their current password, or deleting their account
</p>

### Password

<p align="center"> 
  Allows the user to change their password to a new one
</p>


## Acknowledgments

[EECS 485 Project Description](https://eecs485staff.github.io/p2-insta485-serverside/)

<!-- MARKDOWN LINKS & IMAGES -->
[cplusplus]: https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white
[cplusplus-url]: https://cplusplus.com/
[xcode]: https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white
[xcode-url]: https://developer.apple.com/xcode/
