# Configuration

## What does the configuration consist of?

The configuration consists of 5 components:

- Boards
- Groups
- Cards
- Elements
- Commands

These components each relate to another in a chain, which then forms the entire application.

## Boards

Boards are the main component, and an example of a Board can be `Living Room`. Boards don't necassarily have to be rooms, they can be whatever fits your need. Maybe it makes sense for you to have a Board, where you can control all of the lights in the house; that freedom lies in your hands.

Boards consists of Groups.

## Groups

Groups are what you will find inside of a Board. As the name suggests, this is a component where you're grouped things together. This might mean that you have a group consisting of all the lights in your house. Again, the freedom lies in your hands.

Groups consists of Cards

## Cards

To continue the previous example of grouping lights together, you would use a Card for every light. A Card is what defines a device. Firstly it is what decides what should show up in the UI, secondly it also contains everything related to a device, like what state and commands it has.

Example: You have a light in your living room, that can be turned on or off. A Card will contain information, saying that it should show a toggle button in the UI. It will also save the state, so you can see in PolyHome whether or not the light is turned on. Lastly, the Card knows that it only has one command: the command to toggle the light on or off.

Cards consists of Elements

## Elements

An Element is what will actually show up in the UI. This can be something like a toggle button, a text field, or something completely else. This project utilises what is called Web Components, meaning that the sky is the limit!

In the navigation menu you will find a section dedicated to Elements.

## Commands

As mentioned Cards need a Command in order to do anything, other than just be shown. This is where a Command comes into play. A Command contains the low-level specific information about how an action should be executed, meaning this is also where it gets more technical.

Continuing the light analogy; let's say you turn your light on by sending an HTTP request to it. A Command is where you'd define the address the HTTP request needs to be sent, what params it might giving, headers, body etc.

In the navigation menu you can find an entire section dedicated to Commands.