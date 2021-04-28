## **Table of Contents**

* [Overview](#overview)
* [Approach](#approach)
* [Use Case Ideas](#use-case-ideas)
* [Beyond The Basics](#beyond-the-basics)
* [User Guide](#user-guide)
* [Developer Guide](#developer-guide)
* [GitHub Organization](#github-organization)
* [Deployment](#deployment)
* [Page Mock Ups And Screen Shots](#page-mock-ups-and-screen-shots)
* [Project Board](#project-board)
* [Team](#team)

## **Overview**

<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;The Goal of this project is to create an app that would enable students and faculty of The University of Hawaii at Manoa campus to easily search for places to eat, based on their cravings for the day, for example, if the user want to grab a coffee in the morning the user can search within the app and the app would show all the available coffee shops within the campus, or if the user wants to have a healthy meal replacement smoothie for lunch, the user would be able to search for that as well, and lastly, if the user wants to have pizza for dinner they would be able to locate a place that serves pizza for dinner. The app would also empower the user to find out what specific days a favorite dish of theirs is being served at a specific restaurant of their choosing. The app would also enable the user to do the following within the app:
</p>
* Allow the user to log in using their UH credentials
* Show specific menu items available at the current time and show the locations of those places.
* Show general menus available throughout the day on any specific day.
* Be able to check what forms of payment the location accepts(i.e. Apple pay, UH dining credits, AMEX.)


## **Approach** 

<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;The app should be able to provide a landing page in which an image would show a potential highlight of a specific restaurant for the day. The app would also provide a navigation bar at the top of the landing page in where it would show the organizations logo at the top left of the screen and the center screen would provide the navigation around the website and lastly on the far top right of the screen would show social media links and login information and/or option. The Navigation bar would display links to restaurants, food trucks, and other food options around the campus. In the end the app layout would have all the following information:
</p>
* Landing Page (Restaurant Highlight)
* User Home Page / Profile
* Vendor Home Page / Profile
* Admin Home Page
* Add Vendor Page
* Link to Vendors HomePage Via Navigation Bar
* Food Availability
* Food Searches
<p align="justify">
The app would then also contain a footer menu in which it would display a contact us, about us, and so forth.
</p>

## **Use Case Ideas**

<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;Whether or not the following bullet points list all pages or not, the completed use case should show an end-to-end scenario of using the system.</p>

* New user goes to landing page, logs in, gets home page, sets up profile.
* New vendor goes to landing page, logs in, gets  home page, sets up profile.
* Admin goes to landing page, logs in, gets home page, edits site.
* User goes to landing page, logs in, looks for food to buy.
* Vendor, goes to landing page, logs in, edits online store.
* User is notified of daily menu changes and food items that matches their preferences.

## **Beyond The Basics**

After implementing the basic functionality, here are ideas for more advanced features:
* Notify students via email, twitter, SMS when particular food choices are available.
* Automated updating of menu items from vendors. For example, they agree to post their daily specials via twitter, and your application retrieves their twitter feed and uses that data to update their page.
* Allow students to rate menu items.
* Integrated map functionality; note that some food trucks change their location over the course of a week.
* Provide feed of tweets from vendors (some vendors might use Twitter to advertise daily specials and locations.)

## **User Guide**

### Landing Page
<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp; The user is greeted with a landing page as can be seen below. From the landing page the user is able to browse through all the available food venues within the University Of Hawaii at Manoa campus, they are able to view the menus available specific to the day the user is viewing the website and ommitting the display of all other food venues that are currently closed or are off campus, they are able to select a top picks section, in which the user can see the most popular choices based on other users interests, and lastly, the user is able to login to their user profile or create a profile if they are not a current user.
</p>
<img class="ui large image" src="/image/landing-page-draft.png">

### Venues Page
<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp; Within the venues page the user is able to view all the available food venues within the campus. each card displays the food venues name, their location, the hours of operation, and a brief description about their venue. An image of the Venues page can be seen below.
</p>
<img class="ui large image" src="/image/venues-04-27.png">

### Today's Menu
<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp; The Today's Menu page will display all available menus of venues available on the campus for that specific day that the user is using the site. The Today's Menu is displayed as such that each venue card will display the venues logo and what is being served for that day with each specific venue allowing the user to scroll through the many choices availabel. A sample image of the layout of the Today's Menu can be seen below.
</p>
<img class="ui large image" src="/image/todays-menu-04-27.png">

### Top Picks
<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp; The top picks page will display to the user all available venues but based on preferences(i.e. Chinese, Local, Hawaiian, or Korean). Each preference will have a specific card and will display specific venues that offer that preference.
</p>
<img class="ui large image" src="/image/top-picks-04-27.png">

### Login
<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp; Login allows the user to either login to their current profile or signup to create a profile. When creating a profile the page will also ask the user their role, for example, if they are a student, admin, or a vendor. With the designation the user will be able to make specific changes depending on their role. If the user selects the role of student, they would only be able to make edit regarding their user profile, If the user selects the role as a vendor the vendor would be given access to edit their vendor page or add their food establishment to the list of venues from the Vendor page. If the user selects admin, they would be granted full access to the site and make any needed changes to the site. The Login and sign-up pages can be seen below, once the user successfully creates a profile the user will be re-directed to a form for the user to fill out.
</p>
 <table style="padding:10px">
  <tr>
    <td align="center">Login Page<img src="/image/login-04-27.png"></td>
    <td align="center">Sign-Up Page<img src="/image/signup-04-27.png"></td>
  </tr>
</table>
<table style="padding:10px">
  <tr>
    <td align="center">Login Drop Down Option<img src="/image/login-dropdown-04-27.png"></td>
    <td align="center">Existing User Error<img src="/image/signup-error-04-27.png"></td>
  </tr>
</table>

### Adding A Profile Form
<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp; When creating a new profile and the users email has be checked against the database and no such email exists, the user will be redirected to a form for the user to fill out, which can be seen below. Once the form has been filled out a pop-up window will be displayed indicating that the profile has be successfully been created and added to the database.
</p>
<table style="padding:10px">
  <tr>
    <td align="center">Sign Up Form<img src="/image/signup-form-04-27.png"></td>
    <td align="center">Sign-Up Success Page<img src="/image/signup-success-04-27.png"></td>
  </tr>
</table>

### User Profile
<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp; The User Profile displays the user information with their information, such as, their email, title, bio, and their preferences in food. The user will be able to edit their profile as they see fit with the edit button.
</p>
<img class="ui large image" src="/image/user-profile-04-27.png">


## **Developer Guide**

## Installation

First, [install Meteor](https://www.meteor.com/install).

Second, download a copy of [grub-n-go](https://github.com/grub-n-go/grub-n-go).

Third, cd into the app/ directory of your local copy of the repo, and install third party libraries with:

```
$ meteor npm install
```

## Running the system

Once the libraries are installed, you can run the application by invoking:

```
$ meteor npm run start
```

The first time you run the app, it will create some default users and data. Here is the output:

```
meteor npm run start

> bowfolios@ start D:\github\michaelrpierce\grub-n-go\app
> meteor --no-release-check --exclude-archs web.browser.legacy,web.cordova --settings ../config/settings.development.json

[[[[[ ~\D\github\michaelrpierce\grub-n-go\app ]]]]]

=> Started proxy.
=> Started MongoDB.
W20210427-21:21:49.170(-10)? (STDERR) Note: you are using a pure-JavaScript implementation of bcrypt.
W20210427-21:21:49.845(-10)? (STDERR) While this implementation will work correctly, it is known to be
W20210427-21:21:49.847(-10)? (STDERR) approximately three times slower than the native implementation.
W20210427-21:21:49.848(-10)? (STDERR) In order to use the native implementation instead, run
W20210427-21:21:49.848(-10)? (STDERR)
W20210427-21:21:49.849(-10)? (STDERR)   meteor npm install --save bcrypt
W20210427-21:21:49.850(-10)? (STDERR)
W20210427-21:21:49.851(-10)? (STDERR) in the root directory of your application.
I20210427-21:21:57.018(-10)? Creating default Profiles.
I20210427-21:21:57.019(-10)? Defining profile johnson@hawaii.edu
I20210427-21:21:57.957(-10)? Defining profile henric@hawaii.edu
I20210427-21:21:58.287(-10)? Defining profile cmoore@hawaii.edu
I20210427-21:21:58.612(-10)? Defining profile achriste@hawaii.edu
I20210427-21:21:58.941(-10)? Defining profile leighj@hawaii.edu
I20210427-21:21:59.264(-10)? Defining profile sin8@hawaii.edu
I20210427-21:21:59.609(-10)? Creating default Vendors.
I20210427-21:21:59.610(-10)? Defining profile panda@foo.com
I20210427-21:22:00.401(-10)? Defining profile spot@foo.com
I20210427-21:22:00.810(-10)? Defining profile crepe@foo.com
I20210427-21:22:01.134(-10)? Defining profile lnl@foo.com
I20210427-21:22:01.463(-10)? Creating default Projects.
I20210427-21:22:01.464(-10)? Defining project Open Power Quality
I20210427-21:22:01.763(-10)? Defining project RadGrad
I20210427-21:22:01.768(-10)? Defining project WRENCH
I20210427-21:22:01.777(-10)? Defining project Cyber Canoe
I20210427-21:22:02.423(-10)? Monti APM: completed instrumenting the app
=> Started your app.

=> App running at: http://localhost:3000/
```


### Note regarding "bcrypt warning":

You will also get the following message when you run this application:

```
Note: you are using a pure-JavaScript implementation of bcrypt.
While this implementation will work correctly, it is known to be
approximately three times slower than the native implementation.
In order to use the native implementation instead, run

  meteor npm install --save bcrypt

in the root directory of your application.
```

On some operating systems (particularly Windows), installing bcrypt is much more difficult than implied by the above message. Bcrypt is only used in Meteor for password checking, so the performance implications are negligible until your site has very high traffic. You can safely ignore this warning without any problems during initial stages of development.


### Viewing the running app

If all goes well, the template application will appear at [http://localhost:3000](http://localhost:3000).  You can login using the credentials in [settings.development.json](https://github.com/grub-n-go/grub-n-go/blob/master/config/settings.development.json), or else register a new account.

### ESLint

You can verify that the code obeys our coding standards by running ESLint over the code in the imports/ directory with:

```
meteor npm run lint
```

### Resetting the Database

You can clear the system data to re-intialize default datas using:

```
meteor reset
```

## **GitHub Organization**
* [Grub-N-Go Organization](https://github.com/grub-n-go/grub-n-go)

## **Deployment**
* [Digital Ocean Deployment of Grub-N-Go](https://grubngo.xyz/)

## **Page Mock Ups And Screen Shots (Updated: April 15, 2021)**

### **Landing Page**
<img class="ui large image" src="/image/landing-page-draft.png">

### **Venues**
<img class="ui large image" src="/image/venue-page-mockup.png">

### **Top Picks**
<img class="ui large image" src="/image/Top-Picks-Page-Mockup.png">

### **Sign-In**
<img class="ui large image" src="/image/signin-mockup.png">

### **User Profile**
<img class="ui large image" src="/image/userprofile-mockup.png">

### **Add User Profile**
<img class="ui large image" src="/image/adduserprofile-mockup.png">


## **Project Board**
* [M1](https://github.com/grub-n-go/grub-n-go/projects/2)
* [M2](https://github.com/grub-n-go/grub-n-go/projects/5)

## **Team**

Grub-n-Go is designed, implemented, and maintained by [Ryan Vizcarra](https://ryanv048.github.io/), [Kristine Rivera](https://tineriver.github.io/), [Karl Penuliar](https://karlp1998.github.io/) & [Michael Pierce](https://michaelrpierce.github.io/)
