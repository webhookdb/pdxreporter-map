# pdxreporter-map

Map for PDX Reporter using WebhookDB.

This code was build for the tutorial at <https://docs.webhookdb.com/guides/render-map/>.

## Demo

Check out <https://webhookdb.github.io/pdxreporter-map>.

## Development

It's just an HTML file. You'll need to serve it from localhost so the Mapbox token works.

    $ python3 -m http.server

Then open a browser to <http://localhost:8000> and the map will load.

Contributions on map styling are welcome and do not require anything beyond a browser and text editor.

If you want to modify the SQL query that supports this page,
you can set up your own WebhookDB account and feed.
