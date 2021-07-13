# R1
## Description of your website, including:

## Purpose
This full-stack web application came to be when we were approached by our client - the owners of a small Korean restaurant. They were a young couple who had opened a Korean restaurant in the Melbourne CBD in 2019. Their business has been thriving and increasing since their opening because of the delicious food,quick service that they provided and affordable prices. With the COVID pandemic starting in March 2020 however, the client found that they needed to adapt their online presence to fit in with the current and ever-changing COVID restrictions. It was with this purpose that the client sought our team and commissioned us to create a better web application that would scale and adapt with their increased sales and the constantly evolving COVID restrictions and regulations.

This web application serves to fulfill two main purposes. Firstly, it will be a web portal where potential diners and customers can access the website to get more information about the restaurant, information like the restaurant's address, menu, contact number, pictures of food etc. Secondly, in-line with the COVID-safe restrictions, diners are able to use this web portal to book a table and timeslot and input their contact details for easy contact tracing should the need arise.

Before hiring our team to make this application, the restaurant's online presence consisted of an Instagram page. So if potential diners wanted to access information like the menu, opening hours etc it was all shown on their Instagram profile description. And when diners wanted to book a spot, they had to Direct Message(DM) the restaurant owners via Instagram or call in. In essence, this was not the most user-friendly booking system for a restaurant as it was reliant on a back and forth in a Instagram DM conversation or with a phone call, making the whole booking process inefficient and pulling our client's attention away from cooking or serving the diners. This was also further complicated by COVID restrictions and their restaurant becoming popular and attracting increasingly more diners. 

As the diners increased and restrictions tightened, this meant that keeping track of the contact details of the diners was difficult as they came from two different sources (Instagram DMs and calling in) and it was on the couple to store that data in an easily accessible place should the information become necessary for contact tracing. Furthermore, potential diners were accustomed to a more official booking system where they received an e-mail confirmation of their booking and were able to easily manage their booking should the need to update or cancel a booking arose. With a booking system in place, the clients would then able to maximize the space that they have and be assured that they are not unnecessarily turning away potential diners and losing business while also having the confidence that they are operating safely within the current COVID restrictions.

In discussion with the client, they decided that it would be easier to have a separate website (that's not on Instagram) for their restaurant that would have the booking system on it. The client would have a secure dashboard where they could easily view the current bookings that are in place at the time of them viewing it and prepare the restaurant accordingly, they will not have to worry about the storing of bookings and contact details anymore but be able to refocus on making delicious food. The booking system will also improve the user experience of the diners and further encourage them to come back again making it a win-win situation.


## Functionality / features

**Main Web Portal**
* Lists Opening Hours
* Lists Contact Number
* Lists Restaurant Address
* Shows Menu
* Shows Gallery (has pictures of food)

**Booking**
* Ability to specify number of people in your party (up to 5)
* Ability to select a date to dine-in
* Ability to select a time to dine-in
* Ability to input contact details like
    * First Name and Last Name
    * Email
    * Phone Number
* Ability to save the contact details in a login to speed up future bookings and allows for updating and managing of the current booking.

**Client:** 
* Has dashboard to look at to view the current bookings
* can update the booking settings on the dashboard
* Can update website information e.g. changes to the menu, opening hours 

## Target audience

This application is aimed towards two main groups. 

**1) The restaurant owners**

This is a young couple who started their business end of 2018 to early 2019. They are both relatively new to the restaurant business but have a passion for cooking delicious and affordably priced food. 

They are fairly tech savvy but would like to further upgrade their current online presence so that they can more easily and efficiently handle the increase in diners while safely operating in accordance with the current COVID restrictions.

The clients will have access to the dashboard for the booking system which grants them administrative privileges so that they can update the booking settings as they see fit.

Another thing to consider is that contact details of the diners will be stored in an easily accessible way. In this way, should contact tracing need to be done, the clients will have the information ready and available for the Victorian government to utilize.

**2) The diners**

The diners will represent the potential and returning customers of the restaurant.

With this target audience in mind, the website would be formatted in a standard way in the style of other popular restaurant sites. This is to ensure that navigation of the website is intuitive and is set up in a user-friendly way to encourage new and repeat diners.

The focus of the booking system format and functionality will keep this target audience in mind as they will be the primary ones using it. 

## Tech stack

**Front-end**

* React (Framework)
* HTML
* CSS
* Javascript

**Back-end**

* Ruby on Rails (Framework)

**Database**

Postgresql

**Deployment**

*Back-end* : Heroku

*Front-end* : Netlify

**Version Control**
* Git
* Github

**Image Upload**
* AWS S3 Bucket

# R4
## 	User Stories
‘persona, what and why'

outline meaningful features of project

Shows evidence of user story revision and refinement.

---

Initial research

User 1:

As a *foodie*, I want to be able to see the menu and the pictures of the food before I make my decision to dine in this place. So I access the **gallery** and the **menu** on the web portal to see if the dishes are to my liking.

User 2:

As a *late-night eater*, I want to check the **opening hours** from the website to see if my favourite korean eatery is still open.

User 3:

As an *anxious diner* I want to get the **contact number** of the restaurant to be assured by the owners that they are abiding by the current COVID restrictions.

User 4:

As *someone unfamiliar with the area*, I want to get the **restaurant address** to input into Google Maps so that I can easily find the restaurant in this new area.

User 5:

As *someone who is organizing a proposal*, I use the **booking system** to be sure that I am guaranteed a table in this popular eatery with my (hopefully) future fiancée. 

User 6:

As *frequent diner* of the Korean eatery, I use the **save contact details in a login** function so that I can easily make repeated bookings with just a few clicks.

User 7:

As the *kitchen manager* I want to be able to estimate how much food that needs to be prepared, so I pull up the **booking system** on my **dashboard** and see how many potential diners I will have.

User 8: 

As the *host/hostess* at the Korean eatery, I pull up the **booking system** so that I can confirm that the diner that just came in did have a booking with our restaurant for this timeslot.

User 9:

As the *chef* I 