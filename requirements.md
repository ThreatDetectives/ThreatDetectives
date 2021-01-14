# Vision
We are creating a tool to help people identify threatening language online. This tool can be used to sound the alarm to potential civil unrest. The goal is to help save lives by being prepared for violence if it is announced previously online. 

# Scope
- In : 
  - This tool will scrape an input URL.
  - Take the langauge and run it through our AI
  - It will return a threat precentage back to the user
- Out : 
  - This tool will not expose or save any sensitive information about the target's personal life that isn't already public
  - The AI will not learn from the input URLs
  - Our product will not be avaible as a mobile app
  - The AI will not crawl the internet

# Minimum Viable Product
- An AI that will learn behavior from a selected data set to return a percentage that is based on threatening language.
- The training database will be able to hold multiple data sets in the order to change the type of language it can search for.
- This AI will work with Facebook and/or Twitter only
- A simple and clean user-interface delpoyed to Heroku

# Stretch Goals
- Add full CRUD capability so that the user may take notes and save them to a database
- An "About the Devs" Page
- Add access to more API's 
- Further training for the AI to provide more accurate results
- Multiple databases for different types of threats 
  - ex: sex-traffic
  - give an API reading for each of different databases
    - the API search will return a threat percentage for each database 

# Functional Requirements
- A user can input a comaptible URL and recieve a percentage back

# Data Flow
- The user input an URL
- The AI scrapes the URL and take a tally of any threatening words or phrases it finds
- The AI will then return the threat percentage to the user

# Non-Functional Requirements
- Security is be ensured because the AI will not be saving any data that is scraped.
- Maintainability will be ensured through the database that will hold the training data that teaches the AI by allowing more data to be included which will improve the accuracy of the results.
- Understandability is maintained by keeping a very simple UI design and one, easily-read result is returned.

