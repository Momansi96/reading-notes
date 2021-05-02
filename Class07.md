# Class06

[Return to home page](https://momansi96.github.io/reading-notes/). 

## Domain Modeling: 

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

#### Model epic fails videos: 

Imagine you've been tasked to build a program that models the popularity of epic fail videos. After months of painstaking research, you've determined that the two essential metrics for gauging popularity are an epic rating and whether or not the video has animals.

Since you'll be modeling the popularity of many types of videos. you'll want to build self-contained objects with the same attributes and behaviors. That way, when you need to change the algorithm for determining popularity, the changes will be small and targeted.

#### Generate random numbers: 

To model the random nature of user behavior, you'll need the help of a random number generator. Fortunately, the JavaScript standard library includes a "Math.random()" function for just this sort of occasion, As you can see, methods can be added to a constructor function's prototype. Think of the prototype as an object's stunt double. Whenever a scene is too dangerous, you can substitute in the prototype to do the work. 

#### Calculate daily Likes: 

Popularity of a video is measured in Likes. And the formula for calculating Likes is the number of viewers times the percentage of viewers who'll Like a video. In other words, viewers times percentage, To calculate the number of viewers per day, generate a random number between 10 and 30 and then multiply it by the epic rating of that video.

#### Summary: 

Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Here's some tips to follow when building your own domain models.

 1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and  behaviors.
 2. Model its attributes with a constructor function that defines and initializes properties.
 3. Model its behaviors with small methods that focus on doing one job well.
 4. Create instances using the new keyword followed by a call to a constructor function.
 5. Store the newly created object in a variable so you can access its properties and methods from outside.
 6. Use the this variable within methods so you can access the object's properties and methods from inside.









