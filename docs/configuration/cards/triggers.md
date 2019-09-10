# Triggers

# What is a trigger?

When someone develops a new Element for PolyHome, the element can normally only do certain things. A toggle button can only be toggled, a button can only be pressed etc. The author of these Elements need to define some triggers that corresponds to the possible actions.

# Example

## ph-toggle-btn

In the case of the offical toggle button `ph-toggle-btn`, it only has a single trigger: `toggle`. When you make define a new Card in your configuration, you will have to map this trigger to one of the Commands you have available. You may have a Commmand with the `id` of `living-room_light_toggle`, which as the name suggests, will toggle the lights in your living room.

Once mapped, `ph-toggle-btn` basically doesn't care what Command you give it, it will simply execute the given Command, being to toggle the living room lights in this case, and change the state.
