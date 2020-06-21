# Project Title

Social media Network

## Overview

The idea of the project is summarized in how to make classify  posts and determine which is spam or not and if spam, this post must be discarded else insert post in database 

Ai model run on database and use it to classify post 

Make frontend form where each user can post in it and pass this post to ai model to classify it and determine number of like in this post

### Database Team

- Ammar Shaalan.
- Mostafa Mahmoud.
- Asmaa Mohamed.



### Business Rules

1. User:
	 -	User must have unique ID (primary key).
	 -	User must have Full Name.
	 -	User must have password.
	 -	User must have unique Email.
	 -	User may have profile picture.
	 -	User must have status.
	 -	User must have type.
	 -	User may have last time login.
	 
	 
2. Posts:
	  -	Post must have user ID (foreign key).
	  -	Post must have unique ID (primary key).
	  -	Post must have content. 
	  -	Post must have published date.
	  -	Post must have type.

3. Likes:
	 - Like must have ID.
	 - Like must have post ID.
	 - Like must have user ID.
	 - Like must have type.

4. Comments:

	 - Comment must have ID.
	 - Comment must have Post ID.
	 - Comment must have User ID.
	 - Comment Must have publish time.
	 - Comment must have content.


5. Profiles:

	 - Profile must have Profile ID.
	 - Profile may have BirthDate.
	 - Profile may have Gender.
	 - Profile may have Career.
	 - Profile may have Country.

6. Admin log:

	 - ADMIN must have an ID. 
	 - ADMIN must have action time.
	 - ADMIN may have object ID.
	 - Admin must have object representation. 
	 - Admin must have action flag.
	 - Admin must change message.
	 - Admin must have user ID.





## Description

- User may publish one or many posts.
- User may like one or more posts.
- User may comment on one or more posts.
- User may have a profile.

- Post must be published by only one user.
- Post may have one or more likes.
- Post may have one or more comments.

- Like must be liked by only one user.
	
- Comment must be published by only one user.

- Users see posts from the home page.
- User must log in before creating posts.
- User can create account form registration page.

On registration, a user must supply the following information:

	Username, Email, full name, password.
	Users must have a unique username and unique Email.

On registration, a user may supply the following information:

	Gender, date of birth.
	User may have profile pictures.
	User can edit his account information.
	User may publish one or more posts.
	Each post is published by one user.
	User can like one or more posts.
	User can delete his like on a post.
	Post may have one or more likes.'

Each post must have the following information:

	Publish date, user, number of likes.
	Post may have likes .
	posts may have comments.
	Likes log has full name. 
	Any user can see likes log of any post.
	Posts have a maximum length of 200 char.
	
	

## Finally
 Depending on the above, this is our ERD
 
 
 ![alt text](https://github.com/Web-application-based-on-AI/database_team/blob/master/Er_diagram/ERD.jpg)

