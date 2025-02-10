<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-10T10:07:23Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2sqTKmkg6bLwYGd26MZJ5NOwrf4",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sqTKmkg6bLwYGd26MZJ5NOwrf4"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2sqTJToJ1n389YGHHGrY6SETQsw",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2sqTJToJ1n389YGHHGrY6SETQsw"
				},
				"enabled": true
			},
			"created_at": "2025-02-10T10:07:12Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2sqTJRyeiGNmx0WJj5s3a1I4gjq",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sqTJRyeiGNmx0WJj5s3a1I4gjq"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
