# Commands

As mentioned Cards need a Command in order to do anything, other than just be shown. This is where a Command comes into play. A Command contains the low-level specific information about how an action should be executed, meaning this is also where it gets more technical.

Continuing the light analogy; let's say you turn your light on by sending an HTTP request to it. A Command is where you'd define the address the HTTP request needs to be sent, what params it might giving, headers, body etc.

In the navigation menu you can find an entire section dedicated to Commands.

## What is a Command?

A Command is what makes PolyHome do stuff. Want to turn on your light? You need a Command to do that. There are different types of Commands, and you can read about each of them by finding them in the navigation menu.

On a general level, a Command contains information about how to execute a request. If it's an HTTP Command it will need to know things like the url, what type of request it is etc.

## Examples

Say that you have a light in your living room you want to turn on. Let's also say that this light turn on by recieving a POST request containing the body `{"toggle": true}`. These are exactly the things a Command will need to contain. In short: everything that's relevant to the execution of something, will need to be in the Command.

See more concrete examples in the sections dedicated to the specific type of commands.
