# Live Shared Mobility Workshop

In this workshop we will step through the process of developing an interactive web map that displays real-time micro-mobility data.  

From a practical perspective this will involve the use of [javascript](https://www.w3schools.com/js/) and a number of opensource (and one not-so opensource) libraries.  Specifically this workshop will make use of the following libraries.

  * [Leaflet](https://leafletjs.com/)
  * [Mapbox](https://www.mapbox.com/)
  * [Leaflet Realtime](https://github.com/perliedman/leaflet-realtime)

From a shared mobility perspective, we will displaying available [Lime](https://www.li.me/electric-scooter) vehicles in the city of Washington, D.C.  These data can be accessed through the open application programming interface (API) made available via the [District Department of Transportation](https://ddot.dc.gov/page/dockless-api). The specific URL that we will be using is

  * https://lime.bike/api/partners/v1/gbfs/free_bike_status.json

Every time that a request is made to this URL, a list of all available vehicles are returned.  We will take this data, parse it in real-time, and visualize it on our web every second.

## HTML Template

1. Click on the `index.html` file shown above to view the contents.

2. In your favorite browser (ideally Firefox), navigate to https://codepen.io/pen.  CodePen is a (limited) free live html coding platform.  You can write HTML and view the results all on the same page.  You are welcome to demo CodePen, but I encourage you to create an account so that you can save your work.

## START CODING

Copy the contents of the `index.html` file and past it into the HTML dialog in CodePen (you can collapse the CSS and Javascript dialogs).  Your page should look something like the figure below.

![preliminary index file](https://github.com/ptal-io/LiveSharedMobility/blob/master/workshop_assets/first.png "Preliminary Index Page")
