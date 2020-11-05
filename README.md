# voyager-application

A journal application used to document:
-Country/State/City/Locale destinations (Wishlist & Past trips)
-Note entries for destinations (places to go, things to do, sights to see, etc.)
  -Complete with 'tags' to search through (restuarant, outdoor, music, scenery, night-life)
  -Entries can be compiled and emailed to a friend (either copy/paste OR email app)

Statement: Have you or a friend ever planned or wanted to plan a trip to a new exciting place? 
Where do you start? By asking for suggestions!
We all propbably have a makeshift notepad of places we want to travel one day.
The things we hope to do, that people tell us we should go do, the random highlights we see on social media to 'check out'. 
Usually these things grasp our attention but not our memory. 

Now we will have a dedicated place to categorize and store these random wanderlust thoughts we spontaneously get.
Log your wishlist of things to possibly do on your next trip and actually highlight your interest level, check them off, and more.
Already visted the destination? - save your favorite ones to places you've already gone and rate them for others!
Even better, we can share them with friends without the awkward, 
  'Hey, have you been here? What should I do here? What did you like? Can you make me a list? Etc.'
  With the simple click of a button.
  
# voyage-user stories
Role	                    Task	               Importance
New User	      Signup for a new account	     High
Returning User	Login to my account	           High
New User	      Log new entries to my account	 Medium
Returning User	Share items from my account	   Low
Returning User	View my entries on my account	 Medium
Returning User	Sort my entries	               Low
Returning User	Filter my entries	             Low
Administrator	  View all user accounts	       High
Administrator	  View usage reports             Low
Returning User	Update account information	   Medium

# voyager-wireframes-userflows

Name: Voyager
List of screen names:
-landingPage
-loginPage
-signupPage
-userHomepage
-manageDestinationPage
-addDestinationPage
-manageActivityPage
-addActivityPage

https://github.com/JaredAngel/voyager-wireframes

LandingPage (User starts here / explains the function of the application)
  => SignUpPage (User signs up for new account using valid email/password)
    -User enters valid email/password and clicks submit => userHomepage
    -User enter valid email but no password then submits => error message appears to supply valid password
    -User enter an email that's already taken => message appears that email is taken and prompts user to sign in if it's theirs
    
  => LogInPage (User signs in to existing account with valid credentials)
    -User enters valid email/password and clicks submit => userHomepage
    -User enter valid email but no password then submits => error message appears to supply valid password
    -User enter an email that's not registered => message appears that email is not valid and prompts user to create new account
    
  => errormessage if email/password are invalid or unacceptable

UserHomePage (after signing in/up user is directed here to view their directory of voyages or to create their first)
  => addVoyagePage (User can add a folder directory to store activities for a given voyage/trip)
    => manageVoyagePage
  => manageVoyagePage (User can view or edit existing voyages/trips)
    => addVoyagePage
    => userHomePage
    
ManageVoyagePage
  => addActivityPage (User can add activities with detailed information regarding each and nested under voyage directory)
    => manageActivityPage
    => manageVoyagePade
  => manageActivityPage (User can view or edit existing activities within a voyage directory)
    => manageVoyagePage
