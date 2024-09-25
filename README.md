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

<img width="364" alt="Screenshot 2024-09-25 at 19 02 49" src="https://github.com/user-attachments/assets/9fb256ac-1df3-489d-b4b9-5214a1a72089"><br>

<p align="center"> 
  Also called the <strong>Main Page</strong>, it displays all of the posts that exist within the SQL database at any given time along with information about the post itself (ie. the post's owner, their profile picture, etc.), comments, and the ability to delete one's own comments
</p>

### User Profile

<img width="757" alt="Screenshot 2024-09-25 at 19 06 08" src="https://github.com/user-attachments/assets/f8a6e154-fed2-4042-99f1-bc47db5fd08d"><br>

<p align="center"> 
  Displays information specific to this given user (including the number of posts they have posted, the number of followers, etc.) There are also links that deal with the user's account, all of the posts that the given user has previouly posted, and allows for the creation of a new post.
</p>

### Followers

<img width="375" alt="Screenshot 2024-09-25 at 19 11 07" src="https://github.com/user-attachments/assets/646a0e2f-ce60-41ee-82a8-7fced18d294e"><br>

<p align="center"> 
  Lists each person that is following a given user, including their username and profile picture, along with a button that allows the current logged-in user to follow/unfollow them
</p>

### Following

<img width="324" alt="Screenshot 2024-09-25 at 19 08 40" src="https://github.com/user-attachments/assets/60cb93d0-7759-4017-a03d-6b4e6119527e"><br>

<p align="center"> 
  Lists each person that a given user is following, including their username and profile picture, along with a button that allows the current logged-in user to follow/unfollow them
</p>

### Post

<img width="443" alt="Screenshot 2024-09-25 at 19 16 24" src="https://github.com/user-attachments/assets/324d411d-435b-4eb2-9a05-8483325a3cf7"><br>

<p align="center"> 
  Displays a given post and related information (ie. the post's owner, their profile picture, and the timestamp), its comments, as well as the ability to like/unlike the post and delete your own comment
</p>

### Explore

*Currently working on this portion*

<img width="205" alt="Screenshot 2024-09-25 at 19 21 10" src="https://github.com/user-attachments/assets/bbb0c183-f8de-4afb-b302-64d4b1c57d48"><br>

<p align="center"> 
  Displays users that you are not currently follows and allows you to follow/unfollow them respectively
</p>

### Login

<img width="232" alt="Screenshot 2024-09-25 at 19 14 43" src="https://github.com/user-attachments/assets/e59ffe11-ef4a-4178-983b-912fa20bb3fa"><br>

<p align="center"> 
  Displays buttons that allow a user to login via their username and password
</p>

### Create

<img width="315" alt="Screenshot 2024-09-25 at 19 15 18" src="https://github.com/user-attachments/assets/7266d959-8940-415c-af02-5c0ccd9266b1"><br>


<p align="center"> 
  Allows for the creation of a new user with a specific username, password, and to upload a specific profile picture
</p>

### Delete

<img width="209" alt="Screenshot 2024-09-25 at 19 13 40" src="https://github.com/user-attachments/assets/4683ffd9-84a1-4538-acf0-3da1cb69325b"><br>

<p align="center"> 
  Allows the logged-in user to delete their own account, along with all information associated with them (any posts, comments, likes, and user information)
</p>

### Edit

*Currently working on this portion*

<img width="551" alt="Screenshot 2024-09-25 at 19 18 54" src="https://github.com/user-attachments/assets/bca856f2-e7a5-414c-bacc-4e00e98dd5b6"><br>

<p align="center"> 
  Allows the user to change their account by uploading a new profile picture, changing their current password, or deleting their account
</p>

### Password

<img width="306" alt="Screenshot 2024-09-25 at 19 12 46" src="https://github.com/user-attachments/assets/58cd5229-8934-45e0-a388-7543cbeb6225"><br>

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
