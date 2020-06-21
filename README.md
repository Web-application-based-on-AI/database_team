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
	 - Like must have ID
	 - Like must have post ID
	 - Like must have user ID
	 - Like must have type




## Description

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

