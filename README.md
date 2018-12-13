# HW6-GIFTASTIC
# GifTastic

### Description

In this assignment, you'll use the GIPHY API to make a dynamic web page that populates with gifs of your choice. To finish this task, you must call the GIPHY API and use JavaScript and jQuery to change the HTML of your site.

This app is made of an array of string, each one relating to the topic of Tim Burton. The app will take in the topics in the array and will create buttons on the HTML. When the user submits what they have typed in the search box the page will grab 10 static, non-animated gif images from the GIPHY API and place them on the page. When the user clicks on the still GIPHY images the gif will animate. If the user clicks the gif a second time it will stop playing. Each gif is displayed with a rating (PG, G, R, and so on) this data has been provided by the GIPHY API. 

* The form on the page takes the value from a user input box and will add it to the `topics` array on the top of the page and render a button on the page for the user topic.

![GIPHY](Images/1-giphy.jpg)


### Bonus Goals

1. Ensure your app is fully mobile responsive.

2. Allow users to request additional gifs to be added to the page.
   * Each request should ADD 10 gifs to the page, NOT overwrite the existing gifs.

3. List additional metadata (title, tags, etc) for each gif in a clean and readable format.

4. Include a 1-click download button for each gif, this should work across device types.

5. Integrate this search with additional APIs such as OMDB, or Bands in Town. Be creative and build something you are proud to showcase in your portfolio

6. Allow users to add their favorite gifs to a `favorites` section.
   * This should persist even when they select or add a new topic.
   * If you are looking for a major challenge, look into making this section persist even when the page is reloaded(via localStorage or cookies).

- - -

### Extras

Downloaded a Tim Burton typeface to use as the font-type for this app.


# Copyright
 (C) Chehlsee 2018. All Rights Reserved.
