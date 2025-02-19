<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-19T10:08:09Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2tFtWnw20VzIokiD3CBVBIfC2U7",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tFtWnw20VzIokiD3CBVBIfC2U7"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tFtXScBMHm0S1rOh2VuvMN3KVo",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-19T10:08:09Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2tFtXScBMHm0S1rOh2VuvMN3KVo",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-19T10:08:08Z",
			"hostport": "77d3438cc13e.ngrok.paid:443",
			"id": "ep_2tFtXJPqtUW9ZYkxWQmV3Jzkusx",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2tFtUmMkUO7SqJWPwd1OhEpRFQU",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://77d3438cc13e.ngrok.paid",
			"tunnel": {
				"id": "tn_2tFtXJPqtUW9ZYkxWQmV3Jzkusx",
				"uri": "https://api.ngrok.com/tunnels/tn_2tFtXJPqtUW9ZYkxWQmV3Jzkusx"
			},
			"tunnel_session": {
				"id": "ts_2tFtXL5v0V19oapypuwZ9ErOg8F",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2tFtXL5v0V19oapypuwZ9ErOg8F"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-19T10:08:08Z",
			"upstream_url": "http://localhost:80",
			"url": "https://77d3438cc13e.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-19T10:08:05Z",
			"domain": {
				"id": "rd_2tFtWnw20VzIokiD3CBVBIfC2U7",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tFtWnw20VzIokiD3CBVBIfC2U7"
			},
			"edge": {
				"id": "edgtls_2tFtWn2p2mmDYaDzBuCZqXnXKx1",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2tFtWn2p2mmDYaDzBuCZqXnXKx1"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tFtWtNKrs4bcxvuOcQnijVgFlK",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-19T10:08:05Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
