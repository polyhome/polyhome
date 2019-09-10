# cards.json

## Example file

```json
[
	{
		"_id": "living-room_light",
		"tag": "ph-toggle-btn",
		"state": {
			"toggled": true
		},
		"commands": [
			{
				"trigger": "toggle",
				"_id": "living-room_light_toggle"
			}
		]
	}
]
```

## \_id

This is the id given to the specific Card. Note that this id HAS to specific between all Cards in this file.

## tag

This is the HTML tag of what should show up in the UI. If you've imported the `ph-toggle-btn` in your `elements.json` file, you will be able to use it here. The same goes for any other Element you may have imported.

## state

This is where you define what state the Card should have, the first time it's imported into the database. Note that this should be treated as a default value. Once the Card has been initialised in the database, the state will only be changed there, and this file will not be changed in any way.

## commands

This is where the magic of the Card happens. Every Element has a defined set of triggers it can use. The `ph-toggle-btn` only has a single one; toggle. Given the above example, you are telling the Element that for the `toggle` trigger, it should fire the `living-room_light_toggle` command.

For more on toggles, read the dedicated section [here](../cards/triggers.md)
