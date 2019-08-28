# Cards

## What is a Card?

A Card is what you use inside Groups. Here we move a bit away from the visual, and into the logical. Regarding the visual, the Card contains the tag of the Element, that you want to be shown.

> For more info om Elements, check out the [dedicated page](Elements.md)

On the logical side the Card contains the state, and what Commands the Card should have. While you can technically add any state and any Commands to the Card, it is up to the given Element what it needs, and what you should put in there.

## Examples

### Living room light

Let's say you want to have a Group concerning a light in your living room. You don't just want that Group to be a toggle button, you also want some text, describing what that toggle button is for. Here you would most likely use two Cards:

- One Card that contains the text field, saying something like "Living Room Light"
- One Card that contains the toggle button

The Card with the text doesn't need much. It needs the tag for the Element and a state containing the text it needs to show.

The Card with the toggle button needs a bit more. It of course needs the tag for Element as well. Other than that, it will need the state of the toggle button. If you are using the official `ph-toggle-btn` it will have a single trigger called `toggle`. You can read more about triggers in the [dedicated section](cards/triggers.md)
