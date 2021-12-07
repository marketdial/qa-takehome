# Welcome!
The purpose of this project is to demonstrate your ability use cypress. You will be writing code that opens a headless browser, navigates webpages, and makes assertions along the way.

## Technologies
For this project you will use NodeJS and Cypress (https://docs.cypress.io/guides/overview/why-cypress). You can use any additional libraries/technologies you would like.

## Project Description
Write a single script that accomplishes each of the tasks outlined 

### Part 1
The script should:
 1. Initialize the Cypress library 
 2. Open a headless browser and navigate to google.com
 3. Enter the text "MarketDial" into the search bar and initiate the search
 4. One of the results will be a link to "https://www.marketdial.com/", click that link

### Part 2
Once navigated to the MarketDial home page the script should:
 1. Wait for the page to successfully load
 2. Assert that the text "Applicable for Any Retail Function" is displayed where expected /marketdial-homepage.png

 Bonus: Add any number of optional assertions

### Part 3
From the MarketDial home page
 1. Using the dropdown navigate to `About Us > Events`
 2. Assert that the text circled in the image matches "Using MarketDial, You Can". This assertion will fail because the text does not match /events.png
 
 Bonus: Add any number of optional assertions

### Part 4
Create a `README.md` that at the minimum explains: 
- How to install the requirements for the project
- How to run the project
- How to interpret the results

## How to submit your code
You can submit zip files via email or you could upload the solution to your personal GitHub and share the link with us

## How will we verify this once submitted?
Once your code is submitted we will do the following to verify functionality:
- Follow your instructions on what to install
- Run your code as specified by you
- Verify the base functionality is met

