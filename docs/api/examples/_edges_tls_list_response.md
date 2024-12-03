<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-03T10:06:00Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2phZeHAnUSmkPyNYUl0gp1MhP8y",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2phZeHAnUSmkPyNYUl0gp1MhP8y"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2phZcotkeohlSFq2CrUYDy3QPWW",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2phZcotkeohlSFq2CrUYDy3QPWW"
				},
				"enabled": true
			},
			"created_at": "2024-12-03T10:05:49Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2phZcpcxLH0SxjSu5mx2vCaRoK5",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2phZcpcxLH0SxjSu5mx2vCaRoK5"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
