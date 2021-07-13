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
* has admin privileges and can update the booking settings on the dashboard
* Can update website information e.g. changes to the menu, opening hours 

**Bonus Features**
* The booking system is synced with Melbourne Money. This way when the meal has been paid for the contact details can be transferred to Melbourne Money to simplify the rebate claim process.

## Target audience

This application is aimed towards two main groups. 

**1) The Restaurant Owners**

This is a young couple who started their business end of 2018 to early 2019. They are both relatively new to the restaurant business but have a passion for cooking delicious and affordably priced food. 

They are fairly tech savvy but would like to further upgrade their current online presence so that they can more easily and efficiently handle the increase in diners while safely operating in accordance with the current COVID restrictions.

The clients will have access to the dashboard for the booking system which grants them administrative privileges so that they can update the booking settings as they see fit.

Another thing to consider is that contact details of the diners will be stored in an easily accessible way. In this way, should contact tracing need to be done, the clients will have the information ready and available for the Victorian government to utilize.

**2) The Diners**

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
Initial User Stories

**Persona 1**

**Who:** 

*Foodie diner* persona who is passionate about eating delicious well-made food. 

**Goal:** 

They want to be able to make informed decision on the places they eat in, making sure the restaurant that it is up to their high standards.

**Problem:**

 Most restaurant websites are lacking in detail and not user-friendly.

**User Stories**

* I want to be able to see the menu and the pictures of the food before I make my decision to dine in this place. 

* I want to get the contact number of the restaurant to be assured by the owners that they are abiding by the current COVID restrictions and cleanliness standards.

**Persona 2**

**Who:**

*Efficiency* persona is a person who likes things to be efficient,user-friendly, convenient and easily accessible. 

**Goal:**

Their priority is that eating at the restaurant is the simplest thing in the world and that there is nothing that slows them down unnecessarily.

**Problem:**

They find it hard to know when the restaurant is open and where it's located. They struggle with lack of or counter-intuitive booking systems. 

**User Stories**

* I want to check the opening hours from the website so that I can see if my favourite korean eatery is still open.

* I want to get the restaurant address to input into Google Maps so that I can easily find the restaurant and not lose time finding the place.

* I use the user-friendly booking system so that I am guaranteed a table in this popular eatery. 

* I save my contact details in a login with the booking system so that I can easily make repeated bookings with just a few clicks.

**Persona 3**

**Who:**

The *Kitchen Manager* persona is someone who is responsible for the overall operations back of the house and kitchen area.

**Goal:**

To be able to make preparations for the day's work in the kitchen.

**Problem**

They have been guesstimating on how much food is needed to be purchase and sometimes purchase too much and would like to minimize that.

**User Stories**

* I want to see how many potential diners the restaurant will have so that I am able to estimate how much food that needs to be purchased or ordered in advance.

**Persona 4**

**Who:**

The *host/hostess* is responsible for greeting the customers and seating them at their tables.

**Goal:**
Their goal is to greet and quickly seat diners.

**Problem**
Previously, all the bookings were written in a book and not well organized. 

**User Stories**

* I want access to the confirmed bookings so that I can quickly and easily check that the diner has a booking for this timeslot.

**Persona 4**

**Who:**

The *head chef* persona is the one who oversees the cooking and food preparation.


I want to be able to edit the menu, so that I can cook and serve new recipes to the diners.

User 10:

As the *restaurant owner* I want to make changes to the opening hoursin the web portal to reflect the new working hours that is more financially viable during COVID lockdown.

---

After further consultation with the clients some extra user stories and features were proposed:

User 1:

As the *cashier* and *restaurant owner* I want to encourage the diners to use Melbourne Money so that they become return customers.

User 2: 

As the *restaurant owner* I want admin privileges to make sure that only I can edit the booking system settings and no one else.

User 3:

As the *restaurant owner* I want to have the diner's contact information easily retrievable should the Victorian Government need them.

User 4: 

As the *restaurant owner*, I want the booking settings to sync up with the new COVID restrictions so that I am assured that the restaurant is operating within the regulations.