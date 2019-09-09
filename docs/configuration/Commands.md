# Commands

## What is a Command?

A Command is what makes PolyHome do stuff. Want to turn on your light? You need a Command to do that. There are different types of Commands, and you can read about each of them by finding them in the navigation menu.

On a general level, a Command contains information about how to execute a request. If it's an HTTP Command it will need to know things like the url, what type of request it is etc.

## Examples

Say that you have a light in your living room you want to turn on. Let's also say that this light turn on by recieving a POST request containing the body `{"toggle": true}`. These are exactly the things a Command will need to contain. In short: everything that's relevant to the execution of something, will need to be in the Command.

See more concrete examples in the sections dedicated to the specific type of commands.
