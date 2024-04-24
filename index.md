# BrainBows

## Table of Contents

* [Overview](#overview)
  * [Goals](#goals)
* [Usage Guide](#usage-guide)
  * [Deployment](#deployment)
  * [Landing Page](#landing-page)
  * [User Home Page](#user-home-page)
  * [Calendar](#calendar)
  * [Sign Up Page](#sign-up-page)
  * [Sign In Page](#sign-in-page)
  * [Edit Profile Page](#edit-profile-page)
  * [Office Hours Page](#professor-TA-office-hours-page)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
  * [Project Pages](#project-pages)
* [Potential Issues](#potential-issues)
* [Links](#Links)
* [Contact Us](#contact-us)


## Overview

As Computer Science students, a typical school day is composed of staring at a computer screen which can feel very isolating. The BrainBows app is meant to be an app to encourage studying in groups as opposed to studying alone. While there is nothing wrong with solo study, studying with a partner or in a group can improve material retention and overall boost the mood of a study session. As more students begin to use BrainBows, it will facilitate a sense of community in the UH Manoa computer science department.

Visit our organization page on [GitHub!](https://github.com/brainbows)


### Goals

* To encourage camaraderie and bolster social interaction
* Combat burnout by forming communities
* Through relating with students in similar situations, we aim to make students feel a little LESS lonely
* Ultimately, an improvement in grades and QoL for students

## Usage guide

Documentation and a brief guide app usage.

### Deployment

<a href="https://brainbows.today/">Deployed Brainbows</a>

### Landing Page

Upon first clicking on the URL, the users are led to the landing page which explains usages of BrainBows

<img src="/doc/brainbows-landing.png">

### Sign Up Page

By clicking on the "Login" button in the upper right corner of the navbar, the user is given two options. Selecting 'sign up' will lead the user to the register page. Users can sign up on the register page. The user will be prompted to fill out their name, email, and password. Because this is currently only available for UH students and faculty, we have a UH Email requirement. Also required will be the user's current grade level, the classes that they are currently taking ("grasshopper), and the classes they have taken and consider themselves "senseis" in.

<img src="/doc/brainbows-register-page.png">

### Sign In Page

Alternatively, if the user has already created an account with BrainBows, selecting 'sign in' will lead them to the sign in page where they will be prompted to enter their email and password.

<img src="/doc/brainbows-login.png">

### User Home Page

Upon signing in, the users are led to their homepage which allows them to change their profile, match with other students, track their sessions and change their settings.
<img src="/doc/brainbows-user-home.png">

### Calendar
On the user home page, students can choose to view their calendar. The user is taken to the calendars and events page where it lists all of the events that are coming up, from there the user can simply click on the event to sign up and join the study sessions.

<img src="/doc/brainbows-calendar.png">

### Edit Profile Page

On the user home page, users are able to click on the edit profile button. This will lead them to a page where users are able to view their profile and make any necessary updates.

<img src="/doc/brainbows-edit-profile.png">

### Professor/TA Office Hours

Users will be able to view office hours times of as well as which courses each professor/TA teaches to allow them to schedule an appointment with the right professor/TA.

<img src="/doc/brainbows-updated-office-hours.png">

## Community Feedback

## Developer Guide

First, install Meteor.

Second, visit the BrainBows application github page, and click the “Use this template” button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo. However you do it, download a copy of the repo to your local computer.

Third, cd into the brainbows/app directory and install libraries with:

<pre>
$ meteor npm install
</pre>
Fourth, run the system with:
<pre>
$ meteor npm run start
</pre>
If all goes well, the application will appear at http://localhost:3000.

### Application Design
BrainBows is based upon meteor-application-template-react and meteor-example-form-react..

## Development History

### Project Pages

#### Milestone 1: Mockup Development

For this milestone, HTML pages were created to illustrate rough mockups of what the layout of the system will look like.
[Milestone 1](https://github.com/orgs/brainbows/projects/1)

#### Milestone 2: Implement backend
For this milestone, the main focus was to implement the backend of the pages created in the previous milestone.
[Milestone 2](https://github.com/orgs/brainbows/projects/4)

#### Milestone 3:

[Milestone 3](https://github.com/orgs/brainbows/projects/5/views/7)

## Potential Issues

* Students tend to shy away from assistance

## Links

* <a href="https://github.com/orgs/brainbows/projects/1/views/2">M1 progress</a>

* <a href="https://github.com/orgs/brainbows/projects/4/views/2">M2 progress</a>

* <a href="https://github.com/orgs/brainbows/projects/5/views/7">M3 progress</a>

### Deployment

* <a href="https://brainbows.today/">Deployed Brainbows</a>

* [Contract](https://docs.google.com/document/d/1UTXUBMOhgexRM0GUk0DjcuveB0k8kVmOhDpdFOcIGlo/edit)

* <a href ="https://github.com/brainbows">Github organization page</a>

## Contact Us

BrainBows is designed, implemented, and maintained by <a href="https://braeden-cs.github.io/">Braeden Mendoza</a>, <a href="https://jayssuh.github.io/">Jay Suh</a>, <a href="https://yilamulafeier.github.io/">Yilamu Lafeier</a>, <a href="https://kaelankv.github.io/">Kaelan Valencia</a>, <a href="https://haileyfagaragan.github.io/">Hailey Fagaragan</a>
