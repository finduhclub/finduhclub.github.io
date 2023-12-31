# Find UH Club

<img src="images/landing-page.png">


# Overview

## Problem

UH Manoa has many clubs available for students to join. There is no easy way for students to learn about all the different clubs and what, as well as how to join a particular club.

## Solution

A website that allows students to browse a list of clubs and get information on them. The website must also allow club admins that can change what there club page shows, as well as a super admins who can monitor the website for inappropriate content and make regular users into club admins.

The website should allow filtering of clubs by criteria ie: athletic, art, music.

Users should be able to specify interests and be notified when a club is created that has that interest.

Admins can monitor the website and create new interests.

## User Guide

First thing to do is signup for an account. The landing page should have a signup form on the left side of the screen.  Fill it out and submit. If you use the same email as another person already registered, you will be unable to create an account.
<img src="images/landing-page.png">

You will be redirected to the edit profile page:
<img src="images/edit-profile.png" alt="edit-profile">
Here you can set a username, add a profile picture, select your interest in clubs, and any clubs you are a part of. Once you are done, select view clubs to learn about other clubs on the website.

View Clubs page:
<img src="images/view-club-page.png" alt="view club page">

# Community Feedback
1.  "This website is a game-changer – it effortlessly connects UH Manoa students with diverse clubs, making campus life more accessible and engaging."
2.   "Finally, a user-friendly platform that not only showcases clubs but also puts the power in the hands of admins to personalize content, ensuring a dynamic and welcoming online community."
3.   "The club filtering feature is a standout, providing a tailored experience for students to explore and join clubs that align with their interests effortlessly."
4.   "This website revolutionizes the way UH Manoa students discover and connect with clubs, offering a user-friendly experience that's both efficient and enjoyable."
5.   "This website doesn't just showcase clubs; it's a dynamic, interactive platform that fosters a sense of belonging. The admin features, from personalized club pages to content monitoring, make it a valuable addition to the UH Manoa community."

# Developer Guide

Install [Meteor](https://docs.meteor.com/install.html)
To install and run this application yourself, clone the GitHub repo with this link:
```
https://github.com/finduhclub/finduhclub.git
```
Then run:
```
meteor npm install
```
in the app directory, when that is done, run:
```
meteor npm run start
```
The app is now running on localhost:3000.


## Deployment
A link to our website can be found [here](http://164.92.125.147/)

## Development History

### [Milestone 1](https://github.com/orgs/finduhclub/projects/1/views/1): Mockup
The goal of Milestone 1 was to create mockup pages of the website. Some key pages such as the landing, sign-in, home, and profile pages were drafted as HTML pages. We were also tasked with deploying our created landing page and creating a domain for our project.

Here are our mockup pages for our Milestone 1:

This is our landing page (HTML):
<img src="images/landing-page.png">

This is our sign-in page (HTML):
<img src="images/sign-in.png">

This is our home page (HTML) which is displayed upon successful login. Note that the navigation bar depends on the user's role (regular user, club admin, or super admin):
<img src="images/home-page.png">

This is our view profile page followed by a list profiles for super admins (HTML):
<img src="images/view-profile.png">
<img src="images/list-profiles-admin.png">

This is our edit profile page (HTML):
<img src="images/edit-profile.png">

This is our add clubs page:
<img src="images/mockup-add-clubs-page.png">

This is our search clubs page:
<img src="images/mockup-search-clubs-page.png">

This is our dropdown filter menu page:
<img src="images/mockup-dropdown-filter.png">

This is our club view page:
<img src="images/mockup-club-view.png">

This is our admin manage page:
<img src="images/mockup-manage-clubs.png">

### [Milestone 2](https://github.com/orgs/finduhclub/projects/2):
The goal of Milestone 2 is to increase the functionality of the app from Milestone 1. We needed to add at least one page to read from a database and one page to write to a database. We also had to make sure that our website adheres to testing standards by using TestCafe.

Here is our Add Clubs Page:
<img src="images/add-clubs-page.png">

Here is our View Clubs Page:
<img src="images/view-clubs-page.png">

### [Milestone 3](https://github.com/orgs/finduhclub/projects/3):
The goal of Milestone 3 is to increase the functionality of the app from Milestone 2 by adding multiple records of real data. This also combines with keeping up with using TestCafe tests and making sure the deployment is running smoothly. 

Here is our Manage Clubs Page (Admin):
<img src="images/manage-clubs-page.png">

Here is our Edit Clubs Page (Admin):
<img src="images/edit-club-page.png">

Here is our Change Password Page:
<img src="images/change-password-page.png">

### CI/CD
![ci-badge](https://github.com/finduhclub/finduhclub/workflows/ci-finduhclub/badge.svg)

## About the Members

#### [Joshua Brewer](https://github.com/brewerj3)
#### [Brayden Danielson](https://github.com/bfd2)
#### [Tyler Cho](https://github.com/tycho01)
#### [Emily Pham](https://github.com/empham)
#### [Kaianu Reyes-Huynh](https://github.com/kreyeshuynh)

## Team Contract

Our team contract can be found [here](https://docs.google.com/document/d/17JOV43Aup9_bZ_E9dZ_NoMt8ucx9kaBhIeusmvkyDBg/edit?usp=sharing)

## Special Thanks
Our app is based on [meteor-application-template-react](https://ics-software-engineering.github.io/meteor-application-template-react/). We would like to thank [ics-software-enginnering](https://github.com/ics-software-engineering) for providing us with, and maintaining, this template.
