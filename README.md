## SEIR 1018, Dec 9th 2021

# 99 Bottles of Beer

Build an express application that enables users to count down the number of bottles of beer.

## Instructions

1. Clone this repository.
2. Change into the new directory.
3. Work through the requirements listed below.

You do not need to fork this repository and make a pull request.

## Requirements

- On the home page (`get "/"`), users should see:
  - "99 Bottles of beer on the wall"
  - a link that says "take one down, pass it around"
  - this should link to `/98`, where the number represents the number of bottles left.
- When a number is given in the url (`get "/:number_of_bottles"`), users should see:
  - The number of bottles of beer on the wall (i.e. `98 Bottles of beer on the wall.`)
  - a link to "take one down, pass it around", where the href is number of bottles in the parameter minus 1.
- If there are 0 bottles left, do not show a link to "take one down"
  - Add a link to start over, which directs the user back to the home page.
  
  Once you get it working (95, 94, 93....) and want to test your end message, feel free to start your number at 1 or 2, or raise the interval by a larger number. That way you won't have to hit the button 99 times to test your code!

> You may need to do some further research on Handlebars to get some things working! See if there's a way to create conditionals in Handlebars and if you are able to add any kind of style in!

