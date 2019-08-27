# commands.json

## Example File

```json
[
	{
		"_id": "living-room_light_toggle",
		"protocol": "http",
		"verb": "POST",
		"url": "http://192.168.1.100",
		"body": {
			"toggle": true
		}
	}
]
```

## \_id

This is the id given to the specific Command. Note that this id HAS to specific between all Commands in this file.

## protocol

This defines what protocol the Command should use. Examples could be HTTP or MQTT.

## verb/url etc.

Everything that isn't `_id` or `protocol` is specific to that type of Command. You can find a full overview of different types of Commands in the Command section.
