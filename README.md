# travellog
An interactive map of everywhere you've traveled, with room for image galleries, descriptions and dates. You can see an example (of a very long, complicated travel log) at http://laurenhallden.com/travellog/

## What you'll need

- A place to host these files.
- A [Mapbox](https://www.mapbox.com/) API key (you can register for one for free!).
- A bunch of pictures you want to display.
- The latitude and longitude of all the places you want the site to travel to. (You can find these coordinates by googling a place and dropping a pin nearby, but be warned: Google and Mapbox display coordinates differently, so once you look them up you'll have to reverse the oder of the latitude and longitude for this project).

## What you'll do
- Copy these files to your own URL.
- Give each of your locations its own section, with a unique **section id**.
- Make an **image grid** for each location! I'm using the new CSS Grid here (with some fallbacks for browsers that don't quite support it yet), and it's really easy to make your images line up nicely:
    - The grid is 3 columns and as many rows it needs to fit your images. Use the class names to assign each image a size in the gid. For example, an image with the classes `box box--3x1` will take up 3 columns and one row. There's no need to resize a bunch of images -- they'll be cropped to fit their boxes automatically.
    - Your options are: `1x1`, `1x2`, `2x1`, `2x2`, `3x1`, `3x2`, and `3x3`.
    - You can save your images in the `image` folder.
- Near the end of the `index.html` file, add your **Mapbox API Key**.
- Also near the end of the `index.html` file, add an **array item** for each of your sections. Plunk the location's coordinates here. You can also play with pitch (the camera angle as it looks down at your map), bearing (the direction the camera is looking from), and duration (how fast or slow you want the map to "fly" to this location).
- To add a section header with an icon for a state or country, just give the icon the right class name as defined by [Mapglyphs](http://mapglyphs.com/cheatsheet).
- If you want to share your Travel Log on social media, don't forget to add your Log's url, your Twitter handle, etc in the **meta tags** section at the top of the `index.html` file.

You're done! Have fun!
