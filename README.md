# Instagram Curren Location Photo 
This simple application uses Instagram's API to allow users to view their most recent photos taken at their current location.

**Link to project:** http://recruiters-love-seeing-live-demos.com/

![alt tag](http://placecorgi.com/1200/650)

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, jQuery

Using HTML, CSS, and jQuery, I created a simple applicatioln where a user can log into their Instagram account, authorize their location being used, and then see a stream of photos from their account that were taken at their current location. Users can also view how many likes each of these photos has under each image.

For example, if your current location is at the Museum of Fine Arts, any photos you've taken at that location will appear in your stream.

On the click of a button, the user is redirected to Instagram's login page. Once the user logs into their account, they also gain an OAuth access token from Instagram. The user is then directed back to my app where they are prompted by their browser to allow their current location to be used. Once the user approves their location be used, a stream of photos from their Instagram account is produced containing photos that were taken at their current location.

If no photos were taken at the user's current location, then no photos will appear on the application's stream.





## Optimizations

As of right now, my app works, but it's not the best looking application. I do plan on refactoring it later on, as I want to make it faster and allow more user interactions.

I would make the stream align horizontally instead of a vertical list of images. I also would have liked to add an event listener so that when a user hovers over an image, the location is displayed.


## Lessons Learned:

Setting up a local server in my terminal to run the application and working with the Instagram API was a fairly straightforward process. Once I understood the steps, everything else fell into place.

I also learned how important and beneficial API's can be when creating a web application. 
