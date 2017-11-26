# travellog
An interactive map of everywhere you traveled. You can see an example of (a very long, complicated one) at http://laurenhallden.com/travellog/

## What you'll need

- A place to host this.
- A [Mapbox](https://www.mapbox.com/) API key (you can register for one for free!).
- A bunch of pictures you want to display.
- The latitude and longitude of all the places you want the site to travel to. (You can find this by googling a plce and dropping a pin nearby, but be warned: google and MapBox display lattitude and longitide differently, so you'll have to reverse them).

## What you'll do
- Copy these files to your own URL
- Give each of your locations its own section, with a unique section id.
- Made an image gallery for your location! I'm using the new CSS Grid here (with some fallbacks for browsers that don't quite support it yet), and it's really easy to make your images line up nicely. The grid is 3 columns by howevermany rows it needs to fit your images. Use the class names to assign each image a layout. For example, and image with the classes `box box--3x1` will take up 3 columns and one row.
- At the end of the index file, add an array item for each of your sections. Plunk the location's coordinates here. You can also play with pitch (the camera angle) at it looks down at your map), bearing (the direction the camera is pointing from), and duration (how fast or slow you want the map to fly to this place).
- If you want to make sharing your Travel Log look nice on social media, don't forget to add your url, your Twitter handle, etc in the meta tags section at the top of the index file.

You're done! Have fun!