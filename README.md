# \\\\\\\\\ Flock Code Set //////

## Problem 1

### Getting running locally
- This is a basic HTML/ CSS app. To see it locally on your machine, simply clone or fork this repo. For a step by step on how to fork a repo, see this link: [click me](https://help.github.com/articles/fork-a-repo/)

### Approach
- Instructions specified to make this app using only HTML and CSS (non-interactive), so I used a basic table with static HTML for each todo item.

### Resources
- I relied heavily on Bootstrap documentation to recall the correct classes to use for making a table using Bootstrap. [link to bootstrap tables](https://getbootstrap.com/docs/4.0/content/tables/)
- I used google fonts to make the header font and table titles more aesthetically pleasing

### Next Steps
- I would really like to spend much more time styling this, I have a lot of great ideas from building past todo apps :)
- I would want to make the app interactive using JavaScript. I would ideally like to do this using Angular. More specifically, UI-Router. Having multiple pages to organize the app makes sense to me. Using state provider would allow me to break up my code into reusable pieces. Angular also makes it very convenient to list items (such as todo's), which is why I would use this framework.

## Problem 2

##### ```$('.todo-item').on('click', function(e) { console.log(e) });```
- For this scenario you are targeting a specific class (.todo-item), i.e a singular todo item lets say. The on click trigger event will fire the corresponding function when an item with that class is selected. A good use case for using this scenario would be for a delete function for a specific todo item.

##### ```$(document).on('click', '.todo-item', function(e) { console.log(e) });```
- In my experience thus far, I have only used $(document).ready(). But I can see that this is binding the handler to the document. Perhaps can be used when you want to know when any element has been clicked on the page. I used stack overflow to help with this one: [pretty cool stuff](https://stackoverflow.com/questions/22700664/attach-event-handlers-for-click-event-on-all-elements-in-the-dom). Potentially will affect all elements clicked in the document with class .todo-item? 
