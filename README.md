# mapbox

1. Install a basic `Vue.js` application 
2. Create a basic `Vue.js component` and call it `mapbox.vue`
3. Create a test account on [Maxbox](https://www.mapbox.com)
4. Inside `mapbox.vue` create a connection with the `mapbox api` using [axios](https://www.npmjs.com/package/axios)
5. Get a (world) map from `mapbox` as a large scale image (printable format, somehwere between 3000-6000px) and display the image in the component (no css styling required)
6. Add 3 buttons (without css styling) to change the `mapbox api response` to a different map style (Check the `mapbox api docs` for available map styles). Style selection can be random, just add a possibility to change.
7. add 3 buttons (without css styling) to get a map with `world view`, `europe view`, `and austria view` zoom levels. If `mapbox api` has an option to choose and display certain countries and continents, that would be the best option. If otherwise they don't offer this option you would have to somehow get this done with manual zoom levels.
8. Add a button (without css styling) to display a pin on the map with random hardcoded coordinates. Use a custom pin and send it as a `png` to the `mapbox.api`
