# Code Reading Club agenda

## Reflection (10 mins)
- Note a time the past 2 weeks when you used one of the techniques from the club in your work
- Note a time the past 2 weeks when you used information learned about code in your work

Helping people improve interview technique - by using the code club reading technique instead of whote board for shared code reading exercise.
 order of items- in writing code.

## Exercises
At the start everyone should look at the same code, but as the club evolves you can tackle a bigger bit of code by splitting into sections. These exercises are best carried out when the code can fit on one or two pages but with it being the norm to split in many ways - we hope to invent and discover different exercises.

You will need:
- two printed copies of the code for today's club
- some graph paper - or coloured paper and scissors - or acetate and something to write on it with
- coloured pens, crayons or pencils

### Read  code files (8mins) 
This week we had 4 files

### Discuss code files (12mins)
Comments helpful and informative - is that right to look at them?
Testing a hypothesis - will the tests tell me what the code is supposed to do
There were a lot of tests - seems like they were tesing the API not only their own
function doc comments are in the functions (can be in there for the ast) - so they ship with code
extra thought - you can use your comments as test
lookslike it is in the way but you get used to it
multiline comments and strings use same syntax - not a problem because of indenting
mailgun vs appengine - do they build on each other

### Exercise Interaction with code (10 mins)
1. Colour1 the variables - circle and draw links between instatiation and all uses
1. Colour2 the method/ function calls - circle and draw links between declarations and calls
1. Colour3 the classes - circle and draw links between classes and their instances

#### Discuss the results (10 mins)
1. What patterns are visible from the colors?
1. What parts of the code warrant more attention based on the colors?
- Confused me more than last week
- was expecting to be procedureal but ended up looking like circles
- wanted to visualise output but didn't have time
- variables/ constants turned out to be functions
- we couldn't find any classes but sometimes under the hood some might be intantiated as objects
- traditional CSc model of oop but this code feels more aiming for pure functional
- using typescript but not types
- uses known and understood conventions (like use- and set-) but this is by practice/ convention and not obvious to new people to write this way
- found myself drawing flux / redux cycles on the page

### Content

#### Identify (10 mins)
1. Define what it means to be important and independently identify the 5 lines you consider most important
1. Discuss in the group:
- lines covered by many people?
- lines named but not by a lot of people
- Agree less than 10 of the most important lines

Votes by line number: count
7, 17, 18, 28, 41, 45, 50, : 1
11, 19, 23: 2
47: 3
34, 75: 4

#### Some notes in conversation
- history wasn't history of patients, but browser history - this is an example of convention we take for granted
- where are side effects
- using the patients string in 2 places near each other looks like var but was a translation string
- dispatch event important
- people who writing react a lot took export for granted
- people not as familiar with react went there first
- agree that the core markup generator of patient list item and the side effects most important to understand
- thoughts around what is important when reading vs writing the code

## Wash up (independent after session)
### What worked well
- line numbers!
- the club and conversations

### What worked badly
- ran out of time
- taking notes and facilitating at the same time

## Follow up (2 weeks of elapsed time)
- Identify code for next session, keeping in mind Wash up and Reflection information
- Rob to id some code with comments as tests
- Try to get to the section about independent summary
