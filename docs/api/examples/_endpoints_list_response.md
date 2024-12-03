<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-03T10:05:52Z",
			"hostport": "49cf9a67a752.ngrok.paid:443",
			"id": "ep_2phZdAuPzgZe1m6nXZw9HkIGQ4D",
			"name": "command_line",
			"principal": {
				"id": "usr_2phZakZpeUIxnLL7qzo9OEuyoMu",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://49cf9a67a752.ngrok.paid",
			"tunnel": {
				"id": "tn_2phZdAuPzgZe1m6nXZw9HkIGQ4D",
				"uri": "https://api.ngrok.com/tunnels/tn_2phZdAuPzgZe1m6nXZw9HkIGQ4D"
			},
			"tunnel_session": {
				"id": "ts_2phZdEUSjorjAp4qh8U0o6agCCF",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2phZdEUSjorjAp4qh8U0o6agCCF"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-03T10:05:52Z",
			"upstream_url": "http://localhost:80",
			"url": "https://49cf9a67a752.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-03T10:05:50Z",
			"domain": {
				"id": "rd_2phZcthWHEEwK3ngTTFF9QVY1MQ",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2phZcthWHEEwK3ngTTFF9QVY1MQ"
			},
			"edge": {
				"id": "edgtls_2phZcpcxLH0SxjSu5mx2vCaRoK5",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2phZcpcxLH0SxjSu5mx2vCaRoK5"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2phZd0RnH6WTxojxz6AMT4EWtnO",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-03T10:05:50Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
