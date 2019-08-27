# elements.json

## Example file

```json
[
	"https://cdn.jsdelivr.net/gh/polyhome/ph-toggle-btn@master/",
	"https://cdn.jsdelivr.net/gh/polyhome/ph-text-field@master/",
	"https://cdn.jsdelivr.net/gh/polyhome/ph-button@master/"
]
```

## Strings

The `elements.json` files differs from the others, in that it's not an array containing objects, but instead just strings. These strings are the url to where the Elements are being hosted. As can be seen in the example, these Elements are being imported via jsdeliver.net. However, the Elements can be hosted anywhere, that's accessible from PolyHome. Yes that means you can make an Element and host it on your home network, and it will still work.

## Things to know

There are a couple things to note here.

- The url must be the fully fledged url. This means including `http(s)` and not just the domain name.
- A forward slash MUST be present at the end of the url. This is usually where you will run into bugs.
