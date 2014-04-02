# Drop Template Representation

_**TODO:** Describe an drop template representation._

```
{
  "collection": {
    "href": "http://api.getcloudapp.dev/drops",
    "links": [
      { "rel": "next", "href": "http://api.getcloudapp.dev/drops?filter=active&page=2&per_page=20" },
      { "rel": "next-stream", "href": "http://api.getcloudapp.dev/drops?drop_id=490&filter=active&per_page=20" }
    ],
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
        "href": "http://api.getcloudapp.dev/drops/513",
        "links": [
          { "rel": "collection", "href": "http://api.getcloudapp.dev/drops" },
          { "rel": "canonical", "href": "http://cl.dev/0o3B0U2z0321" },
          { "rel": "icon", "href": "https://secure.assets.my.cl.dev/images/thumbnails/unknown.png" }
        ],
        "data": [
          { "name": "id", "value": 513 },
          { "name": "name", "value": null },
          { "name": "private", "value": true },
          { "name": "trash", "value": false },
          { "name": "views", "value": 0 },
          { "name": "created", "value": "2013-03-20T01:06:33Z" }
        ]
      },
      ...
      {
        "href": "http://api.getcloudapp.dev/drops/490",
        "links": [
          { "rel": "collection", "href": "http://api.getcloudapp.dev/drops" },
          { "rel": "canonical", "href": "http://cl.dev/0U3E470t3U2q" },
          { "rel": "icon", "href": "https://secure.assets.my.cl.dev/images/thumbnails/bookmark.png" }
        ],
        "data": [
          { "name": "id", "value": 490 },
          { "name": "name", "value": "http://google.com" },
          { "name": "private", "value": true },
          { "name": "trash", "value": false },
          { "name": "views", "value": 0 },
          { "name": "created", "value": "2013-01-11T19:03:38Z" }
        ]
      }
    ],
    "version": "1.0"
  }
}
```