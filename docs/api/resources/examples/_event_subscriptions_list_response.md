<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2025-02-10T10:07:18Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2sqTKDEv10h0CODb9CwH97Om3cs",
					"uri": "https://api.ngrok.com/event_destinations/ed_2sqTKDEv10h0CODb9CwH97Om3cs"
				}
			],
			"id": "esb_2sqTKA8Cj25bWXvsXiqKYhNpA9W",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2sqTKA8Cj25bWXvsXiqKYhNpA9W/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2sqTKA8Cj25bWXvsXiqKYhNpA9W"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
