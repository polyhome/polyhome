# groups.json

## Example file

```json
[
	{
		"_id": "living-room_light",
		"classes": ["card", "col-2", "col-md-6", "row-2"],
		"cards": [
			{
				"_id": "living-room_light",
				"classes": ["col-2", "col-md-6", "row-2"]
			}
		]
	}
]
```

## \_id

This is the id given to the specific Group. Note that this id HAS to specific between all Groups in this file.

## classes

Please see the dedicated section on groups for an explanation of this.

## cards

This is where you will define what Cards the Group should contain. Per default they will appear in the Group in the same order, that they are written into the array. This behavior can be changed by specifying the right classes. As mentioned above, please see the dedicated section on Group for an explanation of this.
