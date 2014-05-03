# cool-places

## contribuer

pour ajouter un endroit cool :

```sh
# fork to your github account
$ git clone git@github.com:USERNAME/cool-places.git
$ cd cool-places
$ $EDITOR paris.geojson
# commit, push, and PR!
```

```json
{
  "type": "Feature",
  "properties" : {
    "name" : "la fine mousse",
    "description" : "décrivez l'endroit",
    "type" : "bar || restaurant || musée || divers",
    "tips" : [
      "tip n°1",
      "tip n°2"
    ]
  },
  "geometry" : {
    "type" : "Point",
    "coordinates": [
      0.000000,
      00.000000
    ]
  }
}
```
