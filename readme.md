#YelpCamp

##Initial Setup
* Add Landing Pages
* Add Campgrounds page that lists all campgrounds

Each Campground has:
* Name
* Image

#Layout and basic styling
* Create header and footer partials
* Add in Bootstrap

#Creating New Campgrounds
* Setup new campground POST route
* Add in body-parser
* setup route to show form
* add basic unstyled form

#Style the campgrounds page
* Add a bettery header/title
* make campgrounds display in a grid

#Style the Navbar and Form
* Add a navbar to all templates
* Style the new campground form

#Add Mongoose
* Install and configure mongoose
* Setup campground model
* Use campground model inside of our routes!

#Show Page
* Review the RESTful routes we've seen so farm
* Add description to our campground model
* Show db.collection.drop()
* Add a show route/template

v3:
#Refactor Mongoose Code
* Create a models directory
* Use module.exports
* Require everything correctly!

#Add Seeds File
* Add a seeds.js file
* Run the seeds file every time the server starts

#Add the Comment model!
* Make our errors go away!
* Display comments on campground show page

##Comment New/Create
* Discuss nested routes
* Add the comment new and create routes
* Add the new comment form

##Style Show Page
* Add sidebar to show page
* Display commnets nicely

##Finish Styling Show Page
* Add public directory
* Add custom stylesheet

## Auth Pt 1 - Add User Model
* Initial all packages needed for author
* Define User model

## Auth Pt 2 - Register 
* Configure Passport
* Add Register routes
* Add Register template

## Auth Pt 3 - Login
* Add Login routes
* Add Login form

## Auth Pt 4 - Logout/Navbar
* Add logout route
* Prevent user from adding a comment if not signed in
* Add links to navbar
* Show/hide auth links correctly

## Auth Pt 5 - Show/Hide Links
* Show/hide auth links in navbar correctly

##Refactor the Routes
* Use Express router to reorganize all routes

##Users + Comments
* Associate users and comments
* Save author's name to a comment automatically

##Users + Campgrounds
* Prevent an unauthenticated user from creating a campground
* Save username+id to newly created campground

# Editing Campgrounds
* Add Method-Override
* Add Edit Route for Campgrounds
* Add Link to Edit Page
* Add Update Route

#Deleting Campgrounds
* Add Destroy Route
* Add Delete button

#Authorization
* User can only edit his/her campgrounds
* User can only delete his/her campgrounds
* Hide/Show edit and delete buttons

#Editing Comments
* Add Edit route for comments - /campgrounds/:id/comments/:id/edit
* Add Edit button
* Add Update route

#Deleting Comments
* Add Destroy route /campgrounds/:id/comments/:comment_id
* Add Delete button

#Authorization Part 2: Comments
* User can only edit his/her comments
* User can only delete his/her comments
* Hide/Show edit and delete buttons
* Refactor Middleware

#Adding in Flash!
* Install and configure connect-flash
* Add bootstrap alerts to header

