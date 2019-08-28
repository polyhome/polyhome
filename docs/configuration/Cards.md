# Cards

To continue the previous example of grouping lights together, you would use a Card for every light. A Card is what defines a device. Firstly it is what decides what should show up in the UI, secondly it also contains everything related to a device, like what state and commands it has.

Example: You have a light in your living room, that can be turned on or off. A Card will contain information, saying that it should show a toggle button in the UI. It will also save the state, so you can see in PolyHome whether or not the light is turned on. Lastly, the Card knows that it only has one command: the command to toggle the light on or off.

Cards consists of Elements

## What is a Card?

A Card is what you use inside Groups. Here we move a bit away from the visual, and into the logical. Regarding the visual, the Card contains the tag of the Element, that you want to be shown.

> See [Elements](Elements.md) for more on Elements.
