## Assignment 1 - creating a custom Google Map for a nonprofit

For this assignment, I chose to work on a map for Troy Hill Citizens, Inc., the community group for my neighborhood. This organization is important to me because I am on the board, and I love working with the group to invest in our community. The map coordinates with this photo, which is a mural in the middle of the neighborhood:

And here is the color scheme:

I embedded the map [here](/pascale_GISportfolio/google_map_thc.html)

[
  {
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#bfbeae"
      }
    ]
  },
  {
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#523735"
      }
    ]
  },
  {
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#f5f1e6"
      }
    ]
  },
  {
    "featureType": "administrative",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#c9b2a6"
      }
    ]
  },
  {
    "featureType": "administrative.land_parcel",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#52591e"
      }
    ]
  },
  {
    "featureType": "administrative.land_parcel",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#a68626"
      }
    ]
  },
  {
    "featureType": "landscape.natural",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#52591e"
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#52591e"
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#594036"
      }
    ]
  },
  {
    "featureType": "poi.park",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#52591e"
      }
    ]
  },
  {
    "featureType": "poi.park",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#447530"
      }
    ]
  },
  {
    "featureType": "road",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#d7d7d7"
      }
    ]
  },
  {
    "featureType": "road.arterial",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#bfbeae"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#a68626"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#a68626"
      }
    ]
  },
  {
    "featureType": "road.highway.controlled_access",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#a68626"
      }
    ]
  },
  {
    "featureType": "road.highway.controlled_access",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#a68626"
      }
    ]
  },
  {
    "featureType": "road.local",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#594036"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#dfd2ae"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#8f7d77"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#ebe3cd"
      }
    ]
  },
  {
    "featureType": "transit.station",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#dfd2ae"
      }
    ]
  },
  {
    "featureType": "water",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#cee1f2"
      }
    ]
  },
  {
    "featureType": "water",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#92998d"
      }
    ]
  }
]


https://maps.googleapis.com/maps/api/staticmap?key=AIzaSyD6zuVZpGgpzaj-u0UcS5isIzD6rq12Tdk&center=47.66261656732144,-122.30546931219887&zoom=13&format=png&maptype=roadmap&style=element:geometry%7Ccolor:0xbfbeae&style=element:labels.text.fill%7Ccolor:0x523735&style=element:labels.text.stroke%7Ccolor:0xf5f1e6&style=feature:administrative%7Celement:geometry.stroke%7Ccolor:0xc9b2a6&style=feature:administrative.land_parcel%7Celement:geometry.stroke%7Ccolor:0x52591e&style=feature:administrative.land_parcel%7Celement:labels.text.fill%7Ccolor:0xa68626&style=feature:landscape.natural%7Celement:geometry%7Ccolor:0x52591e&style=feature:poi%7Celement:geometry%7Ccolor:0x52591e&style=feature:poi%7Celement:labels.text.fill%7Ccolor:0x594036&style=feature:poi.park%7Celement:geometry.fill%7Ccolor:0x52591e&style=feature:poi.park%7Celement:labels.text.fill%7Ccolor:0x447530&style=feature:road%7Celement:geometry%7Ccolor:0xd7d7d7&style=feature:road.arterial%7Celement:geometry%7Ccolor:0xbfbeae&style=feature:road.highway%7Celement:geometry%7Ccolor:0xa68626&style=feature:road.highway%7Celement:geometry.stroke%7Ccolor:0xa68626&style=feature:road.highway.controlled_access%7Celement:geometry%7Ccolor:0xa68626&style=feature:road.highway.controlled_access%7Celement:geometry.stroke%7Ccolor:0xa68626&style=feature:road.local%7Celement:labels.text.fill%7Ccolor:0x594036&style=feature:transit.line%7Celement:geometry%7Ccolor:0xdfd2ae&style=feature:transit.line%7Celement:labels.text.fill%7Ccolor:0x8f7d77&style=feature:transit.line%7Celement:labels.text.stroke%7Ccolor:0xebe3cd&style=feature:transit.station%7Celement:geometry%7Ccolor:0xdfd2ae&style=feature:water%7Celement:geometry.fill%7Ccolor:0xcee1f2&style=feature:water%7Celement:labels.text.fill%7Ccolor:0x92998d&size=480x360
