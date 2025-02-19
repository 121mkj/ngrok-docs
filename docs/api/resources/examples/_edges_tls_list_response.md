<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-19T10:08:15Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2tFtYCBBZkhF6um78xkBIdGmict",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tFtYCBBZkhF6um78xkBIdGmict"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2tFtWsxJvZLj8S1zhcWjzeknepe",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2tFtWsxJvZLj8S1zhcWjzeknepe"
				},
				"enabled": true
			},
			"created_at": "2025-02-19T10:08:04Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2tFtWn2p2mmDYaDzBuCZqXnXKx1",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tFtWn2p2mmDYaDzBuCZqXnXKx1"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
