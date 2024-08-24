# fcc-team-stats
This **freeCodeCamp** project exposed me to more **_DOM manipulation_**, **_objects_** and **_nested objs_**, and **_switch statements_**. New concepts I got (re)introduced to include the `Object.freeze()` method preventing any changes to an obj, the `.map()` method which returns an altered copy of an array, default parameters and thank you mucho to the creators of obj destructuring.

### Now about the app:

All the data was stored into one main object. Object destructuring was used to access object properties. Those prop values were then inserted into a player card via the call back function that is passed into the `.map()` method that was called on the `players` array property within the main object. An event listener was  called on the select element via the `change` event, the value of that event was passed in as the condition for a switch statement that filtered then displayed player cards that had data that matched the given condition.
