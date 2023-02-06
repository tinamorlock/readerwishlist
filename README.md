# ReaderWishlist.app
Web application built with Django that allows readers and authors to collaborate on story ideas.
## Introduction
Reader Wishlist is a web application built with Python and Django that uses writing-to-market concepts to help authors connect deeper with the types of stories readers want to read. It is driven by reader-created content that highlights what they'd like to see published in the market.
## Phases of Development
### Phase One
Development and design of main "Story" tool.
(Completed on 2/6/23)
### Phase Two
In the second phase, authors will be able to login and interact with the stories. They will be able to “claim” stories as either works in progress or stories they’ve published. Then they’ll be able to add an author story that connects to that reader story. Part of this phase will also include updating the user accounts to be slated as “author” or “reader.”

Steps to completing Phase Two:

* Edit User sign-up so that users can either choose an Author or Reader role (this is currently manual on the admin back-end). It should put them into their respective groups on the back-end to make permission assignment easier.
* Fix the Story model so that the logged in user gets marked as "Author" of each "Story"
* Add email capability to User Model (they'll be able to add their email address and get notified whenever the "Story" they created is claimed by an Author
* Add Author Story Model that will connect to the reader-created "Story."
### Phase Three
This phase will implement either use of APIs or web scraping to pull in data attached to the #RDRWL hashtag from Facebook, Instagram, Twitter, and TikTok. Twitter will be the priority here.
## Current Status
* Phase One is complete. 
* Phase Two in progress.
### Bugs/Errors/Exceptions
* None outstanding
#### Resolved Bugs
* When listing more than two items from a database query, the third goes outside the div—fixed on 2/5/23 by moving a DIV tag
* Permissions set are not working (logged out users can submit to the database)—fixed on 2/5/23 by removing nav item with if statement for logged out users
## February 2023 Notes
### Site Design
The basic design of the website is in place. Still needs some minor tweaking for desktop browsing, and it also needs to be optimized for mobile.
#### Mobile Optimization
* Removed right-hand sidebar for mobile users (3/5/23)
* Removed some styling to make site look better on mobile
### Forms
The forms for user sign-up and database entry are operational and currently being tested. The initial testing shows that they are working, but the design and development needs some work.
### Blog
The blog is fully operational and is able to accept comments. The form for entering comments needs some tweaking to the design. H
### Stories
A basic version of the story tool is up and working. However, it does lack some functionality that will be implemented in later phases of development. 
### Deskstop Screenshot
![image](https://user-images.githubusercontent.com/117326004/216694909-40f36a47-bc40-4e8f-95be-aae7f039910a.png)
### Mobile Screenshot
![image](https://user-images.githubusercontent.com/117326004/216845594-53ae62f3-c094-45d0-b1e3-a644f591984c.png)
