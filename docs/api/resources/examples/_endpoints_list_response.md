<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-10T10:07:17Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2sqTJTDXDG7P0LDSQ8jYGOgutBo",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sqTJTDXDG7P0LDSQ8jYGOgutBo"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sqTK24AYfvtKfIXkm4hx9ANAfl",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-10T10:07:17Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2sqTK24AYfvtKfIXkm4hx9ANAfl",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-10T10:07:16Z",
			"hostport": "c4a8d085fbcb.ngrok.paid:443",
			"id": "ep_2sqTJs0VBgQvitQzJQHevH0TNCa",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2sqTHSwpKiNKMgz0jti12vkJiYo",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://c4a8d085fbcb.ngrok.paid",
			"tunnel": {
				"id": "tn_2sqTJs0VBgQvitQzJQHevH0TNCa",
				"uri": "https://api.ngrok.com/tunnels/tn_2sqTJs0VBgQvitQzJQHevH0TNCa"
			},
			"tunnel_session": {
				"id": "ts_2sqTJrlcyuySuzYivSkuUatSnSo",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2sqTJrlcyuySuzYivSkuUatSnSo"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-10T10:07:16Z",
			"upstream_url": "http://localhost:80",
			"url": "https://c4a8d085fbcb.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-10T10:07:13Z",
			"domain": {
				"id": "rd_2sqTJTDXDG7P0LDSQ8jYGOgutBo",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sqTJTDXDG7P0LDSQ8jYGOgutBo"
			},
			"edge": {
				"id": "edgtls_2sqTJRyeiGNmx0WJj5s3a1I4gjq",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2sqTJRyeiGNmx0WJj5s3a1I4gjq"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sqTJNqQ0KRh3BhPLfkXWxQPGCF",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-10T10:07:13Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
