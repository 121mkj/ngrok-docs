<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-02-19T10:07:49Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.24xj5fkib7vzay8yv.local-ngrok-cname.com",
			"created_at": "2025-02-19T10:07:49Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tFtV1GAsIomTspeJYdNjXczZ80",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tFtV1GAsIomTspeJYdNjXczZ80"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2tFtUoyWEr3Jz9edSfNNZ9SM6bw",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2tFtUoyWEr3Jz9edSfNNZ9SM6bw"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.24xj5fkib7vzay8yv.local-ngrok-cname.com",
			"created_at": "2025-02-19T10:07:48Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tFtUyS4OWjM7C1p6O3I16VrOGn",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tFtUyS4OWjM7C1p6O3I16VrOGn"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
