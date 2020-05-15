# Code Reading Club agenda (14:05)
Code source: https://github.com/moment/moment/blob/develop/src/lib/create/from-anything.js

## Reminder to note for reflection next session (14:10)
- Between sessions, note times when you notice that code reading club has helped you in your other projects or conversations.

- Practice! New project read completely new code bases never seen before. Directly applicable.
- Google alternate sulutions for client - I found myself underlining 
- Spent last week unfamiliar codebases jvm. groovy grails java. Also project is in french - an extra layer of amusement. Reflection that acrynyms CMS is not a CMS in french.
- You tube video of someone doing work to be able to code without typing due to RSI - voice transcription for writing software. There is crossover here.

### Interaction with code (10 mins) (14:20)
1. Colour1 the variables - circle and draw links between instatiation and all uses
1. Colour2 the method/ function calls - circle and draw links between declarations and calls
1. Colour3 the classes - circle and draw links between classes and their instances

- First time arrows going up.
- Adds to the clutter if I arrow from imports
- Marking 89 as constructor
- What is a class?
- Started marking returns as well as variables etc in the colouring stage. Moticated by conversaion last week about early returns. Could this be another 'pattern' we scan look for in this section?

#### Discuss the results (10 mins) (14:30)
1. What patterns are visible from the colors and connections only?
1. What parts of the code warrant more attention based on the colors and connections


### Content

#### Identify (10 mins) (14:40)
1. If necessary, define / remind in group a meaning of importance
1. Independently identify the 5 lines you consider most important
1. Note down which line numbers people selected individually

This time there was virtually no consensus but as a group we agreed 22,47,88 as being important.
- We talked a lot about why that might be including:
    - Eveolved oever a long time
    - Backward compatibility
    - Not really doing one thing (exports 2 completely different types of function)
    - Returns vs mutations
    -

#### Discuss (10 mins) (14:50)
Take turns in the group, and let every member talk about the code for 30 seconds (or less/more, could also be one sentence each). Try to add new information and not repeat things that have been said, and repeat until people do not know new things anymore.
[Save the last word for me protocol](https://lead.nwp.org/knowledgebase/save-the-last-word-for-me-protocol/)
1. Discuss in the group:
- lines covered by many people?
- lines named but not by a lot of people
- Agree less than 10 of the most important lines

#### Summarize in less than 10 sentences (10 mins) (15:00)
1. Independently write down the essence of the code in a few sentences
1. Discuss in the group
- topics covered by many vs few
- strategies used to create the summary (e.g. method names, documentation, variable names, prior knowledge of system)

WE DID NOT GET THIS FAR - but getting closer.
1. Create a summary together
1. Compare the summary with the available documentation (inside and outside the code)
- identify differences and similarities between the groups findings and the existing

## Wash up (5 mins)
- What worked well
    - Excitement: At the end of the session one member of the group grabbed a plastic box full of pens and held it up to the camera "This is my box of colours!"

- What we want to do better next time
    - Try with a Miro board
    - discuss our stragtegies as well as the summarise the code and the important bits
    - try some Elm
