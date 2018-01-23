# An Introduction to the Emotional Generator!
Are you ever unsure how you feel? Would you like some examples that might help you see how other people react in the same situation? GOOD NEWS! You've discovered an app that solves all of your problems! Click on an emotion to see several examples of it in action. Click on any of the images to animate it; click again to make it stop. Can't find how you're feeling? Add a new emotion to the list!

### How does it work?
The Emotional Generator uses a series of arrays, AJAX calls to the GIPHY API, and Bootstrap for styling. Animated and still states are stored in the data-fields of each div; clicking an image will swap the animated version with the still version and vice versa. Clicking any of the buttons at the top completes an AJAX call to GIPHY for 15 results, and filling out the form completes a jQuery call to add to the array of emotions. These additions are only stored locally and are lost upon leaving or reloading the page.

### Who will use this?
Mostly no one, as it is primarily a classroom exercise. The technologies leveraged are useful; the app itself is not.

### What is the goal?
The ultimate goals of creating this app include:
* Create familiarity with AJAX calls to external APIs.
* Use the data-fields available inside div tags to store additional data.

# Deployment
The code can be used in most web servers; there is no required node or database requirement.

# Screenshot
![Screenshot](http://www.fullstacksteve.com/wp-content/uploads/2017/11/emotion-1.png)

# Credits
Steve Marshall, Sole Developer
* [Steve's Online Portfolio](http://fullstacksteve.com/)
* [Steve's LinkedIn Profile](https://www.linkedin.com/in/sonoa/)