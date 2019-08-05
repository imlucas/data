# Stonington, Maine

## `stonington.places`

> A few of my favorite places in the area

```javascript
module.exports = [
  { _id: 'Stonington, Maine', latlong: [44.1592408, -68.6731339] },
  { _id: 'EL EL FRIJOLES', latlong: [44.305953, -68.671159] },
  { _id: 'Harbor Cafe', latlong: [44.1561619, -68.6646152] },
  { _id: '44 North Coffee', latlong: [44.1561432, -68.6628684] },
  { _id: 'Isle au Haut Mail Boat', latlong: [44.1546851, -68.6606818] },
  { _id: 'Deer Isle Hostel', latlong: [44.2080961, -68.6319351] },
  { _id: 'Coldwater Seafood', latlong: [44.1631218, -68.6590683] },
  { _id: 'Stonington Lobster Co-Op', latlong: [44.1560046, -68.6556063] },
  { _id: 'Crockett Cove Woods Preserve', latlong: [44.172655, -68.7121141] },
  { _id: 'Barred Island Preserve', latlong: [44.1564011,-68.7171572] },
  { _id: 'Lucas\' House', latlong: [44.159235, -68.673123] },
  { _id: 'MD Joyce & Barter Lumber', latlong: [44.2003412, -68.6840132] }
];
```

## GeoJSON

1. [Download the Maine Town Polygon shape files](https://opendata.arcgis.com/datasets/c7fdfaabcffa480c820e8be4a19bb298_2.zip?outSR=%7B%22latestWkid%22%3A26919%2C%22wkid%22%3A26919%7D) 
2. `npm i -g shp2json`
3. `Maine_Boundaries_Town_Polygon.zip Maine_Boundaries_Town_Polygon.geojson`
4. `./extract_stonington_geojson.sh`
5. [`stonington.geojson`](https://gist.github.com/imlucas/d6e728d1962e809379f32173f63d1a66#file-stonington-geojson) is now ready to play with

```bash
curl -o stonington.geojson \
https://gist.githubusercontent.com/imlucas/d6e728d1962e809379f32173f63d1a66/raw/7438a42030c5abba28b6c71769ef44fc532e25d2/Stonington.geojson
```
