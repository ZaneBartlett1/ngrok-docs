<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-12-03T10:05:56Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2phZdlldzZDeswjPt01CnwjJQnv",
					"uri": "https://api.ngrok.com/event_destinations/ed_2phZdlldzZDeswjPt01CnwjJQnv"
				}
			],
			"id": "esb_2phZdgE6vXY7h4psBXTdIxu0ePk",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2phZdgE6vXY7h4psBXTdIxu0ePk/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2phZdgE6vXY7h4psBXTdIxu0ePk"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
