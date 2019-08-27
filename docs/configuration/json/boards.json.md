# boards.json

## Example file

```json
[
  {
    "_id": "living-room",
    "title": "Living Room",
    "icon": "home",
    "groups": [
      { "_id" "living-room_light"}
    ],
    "position": 0
  }
]
```

## \_id

This is the id that you want to give the Board. When using the application this doesn't have a big effect, however do note that an `_id` HAS to be unique within all Boards.

## title

This is what will be shown in the UI in the navigation menu.

## icon

PolyHome uses material icons in the navigation menu. You can find all existing material icons [here](https://material.io/resources/icons/?style=baseline). Simply find the one you like, copy the name, and paste it into the `icon` field.

## groups

Here you will define what Groups should be shown on this Board. You just need to write an `_id` of a group you have defined within `groups.json`. Note that it possible to define a non-existing group here. Doing this will simply not have an effect on the UI.

> Because of the last line above, always check your spelling between here and `groups.json` if a group is failing to show up in the UI

## position

This defines the order of how the Boards show up in the navigation menu. The index starts at 0.
