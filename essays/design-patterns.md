---
layout: essay
type: essay
title: "Coding with Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2023-11-30
published: true
labels:
  - Software Engineering
  - Meteor
  - Design Patterns
---

Created By: Gerardo Hernandez


# Can Coding be Artistic?

<p>
  When we think of art, we often think of taking an inspiration or a prompt and freely evoking our artistic abilities to express ourselves.  So when we're coding, aren't we also taking a prompt and creating a beautiful work of art when we're able to get our webpage or component up and running?  Is there a more satisfying moment, then when you've finished typing feverishly to release this code from your head onto IntelliJidea and the green ESLint check mark is still sitting at the top right of the screen?  Wouldn't Bob Ross be proud of that moment?  Short answer, yes, but the long answer is that we don't want it to be artistic in this way.  For a painting, people need to be able to see and appreciate the uniqueness of the piece.  In coding, the true appreciation comes from people being able to discern what is happening.  For this, we have deisng patterns that we implement.  Coding can be most powerfully created, troubleshot and appreciated when it adheres to design patterns that are standardized.  
</p>
<p>
  If we give a person a prompt for something to code, we can guess that under pressure, the solution will be a violent expression of each of the design principles they know for designing code.  We can be left with something that can resemble art if the final execution runs, to be admired by fellow students, or by the teacher's aides.  We can also be left with a crashing mess, a frustrating reality that can strike at the mere absence of a curly brace.  When the dust settles from both of these instances happening, what is left standing is the code.  The true appreciation of our coding occurs in the design patterns; in the repeatable solutions that make for ease of coding in the face of commonplace problems.  If the code runs, that’s great, how does that get repeated?  If you passed your Work-out of the Day (WOD) for Island Snow, but couldn’t repeat the same for Murphy’s, do you even code, bro?  And in the instance of the crashing program, how can we start to troubleshoot if we don’t have a baseline structure?? A design pattern can simplify and streamline the process of creating and troubleshooting code by offering chunked solutions to small components of a coding “problem.” 
</p>
<p>
  Some of the Design Patterns for a webpage called aloha-trades, a concept for a final project, is to implement a factory solution to publish listings for users, based on properties of those users.  The webpage itself can be thought of like the concept of craigslist, but for University of Hawaii students.  In implementing a factory solution, we have a function to Publish a List of Listings.  The specific group of listings depends on: a. Does this post belong to the user?  b. Is the post approved?  c.  Is the post still available for purchase?.  Based on the criteria of the user that is accessing a publication, the function will publish a different set of Lists.  This grouping makes troubleshooting easy, because as soon as the cards do not abide by the known rules that we established, we can pinpoint the faulty code, and modify it as necessary to incorporate our new criteria and publish the appropriate data for a singular publishing “factory.”  
</p>
<p>
 	And not all implemented patterns have been ideal.  One of the satisfying portions of the final project, has been taking a template and figuring out how to dig ourselves as a group out of the lava flow anti-pattern.  There was a legacy group of listings called Stuff.  There was a Stuffs collection, a Stuff of Stuff, a Stuff and a Stuffs.  Initially, we copied the template, and continued on.  After a while, we realized that there were a group of pages sitting in our repository with no purpose.  Pages and Components that , if left unchecked, were going to cause us a headache to debug later once our code and pages depended on them to run. 
</p>

<img width="100%" class="rounded float-start pe-4" src="../img/Bobross.jpg">
