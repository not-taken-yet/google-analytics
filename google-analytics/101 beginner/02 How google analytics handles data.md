# Website connection

## Ways to add tags

To connect website to Google Analytics, <u>add a tag to the website</u>

- directly add to the website's code
- use a tag management system such as Google Tag Manager

## Process of data flow

Once the tag added, it collects things like below
- information about users
	- device type
	- geographic location
	- how they interact with different pages

<mark>user interactions are processed as events</mark>

## User events examples in website

- first visit
- click of outbound link to leave the site

<hr>

# Mobile app connection

To connect mobile app to Google Analytics, <u>add the Firebase Software Development Kit, or SDK to the app</u>

The firebase works similar to the tags attached to the website mentioned above.

## User events examples in mobile app

- number of users reached a certain level on the game
- how many users made a purchase in the app
- information of the purchases

<hr>

# In the end

1. connect website or app to Analytics
2. **(website)** implement a tag on the website
3. **(app)** use the Firebase SDK

Analytics collects **user interactions** as **events**
- page views
- button clicks
- user actions
- system events

Analytics creates reports using those data in a common language (both web & app)

<u>Many basic interactions with the service are automatically collected as events in GA</u>

<mark>We can create custom events to capture what is unique and important to our business</mark>

Once Analytics processes the data, it can't be changed!