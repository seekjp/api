# Drop Representation

_**TODO:** Describe an drop representation._

```
{
  "collection": {
    "href": "http://api.getcloudapp.dev/drops",
    "links": [ ],
    "template": {
      "data": [
        { "name": "name", "value": null },
        { "name": "private", "value": true },
        { "name": "trash", "value": false },
        { "name": "bookmark_url", "value": null },
        { "name": "file_size", "value": null }
      ]
    },
    "queries": [
      {
        "rel": "filter-drops",
        "href": "http://api.getcloudapp.dev/drops",
        "data": [
          { "name": "types", "prompt": "Types" },
          { "name": "limit", "prompt": "Drops Per Page", "value": 20 }
        ]
      }
    ],
    "items": [
      {
        "href": "http://api.getcloudapp.dev/drops/509",
        "links": [
          { "rel": "collection", "href": "http://api.getcloudapp.dev/drops" },
          { "rel": "canonical", "href": "http://cl.dev/image/2n1p1F2p3l2x" },
          { "rel": "icon", "href": "https://secure.assets.my.cl.dev/images/thumbnails/unknown.png" }
        ],
        "data": [
          { "name": "id", "value": 509 },
          { "name": "name", "value": "scout.jpeg" },
          { "name": "private", "value": true },
          { "name": "trash", "value": false },
          { "name": "views", "value": 1 },
          { "name": "created", "value": "2013-01-11T19:22:17Z" }
        ]
      }
    ],
    "version": "1.0"
  }
}
```