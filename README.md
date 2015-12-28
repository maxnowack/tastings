#Tastings

I track my tasting notes in this repository


## Format

I use the following JSON schema to describe my tasting notes

````javascript
{
  name: "Example", // name of the drink
  properties: { // custom properties (e.g. IBU for beer)
    key: value,
  },
  rating: {
    key: value,
  },
  time: new Date(), // time of the tasting
  comments: "..."
}
````
