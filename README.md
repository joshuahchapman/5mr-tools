## What is 5MR?

A fun way to track nature sightings close to home. Here's the answer from [Jen Sanford](http://www.iusedtohatebirds.com/), who popularized the concept:

> The 5MR is a list of birds (or wildflowers, mammals, lizards, insects, trees, etc.) that you have seen within 5 miles of your home.


## Key Resources

- [Jen's 5MR FAQ](http://www.iusedtohatebirds.com/p/vancouver-5mr.html). You can also find links to the 2019 challenge, Instagram account, etc. there.
- [Facebook group](https://www.facebook.com/groups/2244306435817279/)
- [Birders Slack team](https://bit.ly/2P87vCz). See the **#five-mile-radius** channel.


## Mapping Your 5MR

So how do you know what's included in your five-mile radius? Some intrepid folks<sup>1</sup> have figured out cool ways to depict that.


### Viewing your circle

If you just want a quick look at your circle on a map, you can get that [here](https://www.mapdevelopers.com/draw-circle-tool.php). Type in your address, set the radius to 5 miles, and click "New Circle." Done.

### Saving a map

Some find it handy to have a map of their 5MR saved in Google Maps, where they can access it repeatedly and even while out in the field, using the Google Maps app on a smartphone. This involves generating a KML file for your circle, then uploading it to Google Maps:

1. Find the precise latitude and longitude for the center of your circle. (Typically, your home.) You can do this for example by searching for the address in [Google Maps](http://maps.google.com/). When it displays the location, you'll see the latitude and longitude included in the URL in your browser.

1. Go to [this site](http://kml4earth.appspot.com/circlegen.html). Fill in the proper values, make sure the "Auto refresh" box is NOT checked, and click "Generate Circle." This will cause a .kml file to be downloaded to your computer. Note the name and location of that file.

1. In [Google Maps](http://maps.google.com/), navigate to "Your places," then "Maps," then click "Create Map."

1. Choose "Import," then upload the .kml file you generated for your circle.

Voilà! You probably want to give the map a descriptive name so you can easily find it later. That's all there is to it.

### Adding eBird hotspots

With just a few more steps, you can add the eBird hotspots from your circle to your map too:

1. Download the list of hotspots from eBird. (This is done using the [eBird v2.0 APIs](https://documenter.getpostman.com/view/664302/ebird-api-20/2HTbHW), but you don't really need to know that.) Enter this URL in your web browser - you just need to replace the latitude and longitude values with those of the center of your circle first: `https://ebird.org/ws2.0/ref/hotspot/geo?lng=-97.7593878&lat=35.4823241&dist=8&fmt=csv`

1. Open the downloaded .csv file and add a header row with column names. You can also remove extraneous columns - you only need the latitude, longitude, and location name.

1. Go to the Google Map you created for your 5MR. Click "Add layer," then "Import," and upload the .csv file generated in the previous step.

1. There are a couple prompts to map the columns in your file to fields needed by Google Maps. Follow the instructions and hit "Finish." The hotspots should all show up on your map! That's it!

## Tracking Your Sightings

Of course, you can do this any way you see fit, but eBird provides a handy tool for this: the [patch](https://ebird.org/site/patch). You can create a patch, include all the hotspots and personal locations that are within your 5MR, and eBird will give you easy views of which species you've seen in the patch in the current month, year, and lifetime, much as it does for larger regions.

You do have to know and manually select which locations should be included in your patch. Although we can probably come up with some easier ways to handle that as well....

---

<sup>1</sup>Thank you to Jen Sanford, Dick F. Vreeland, Steve Hampton, and Brodie Cass Talbot!
