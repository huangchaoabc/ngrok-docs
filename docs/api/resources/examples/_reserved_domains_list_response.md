<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2sqTHQq8rxsQQAyKi4jpNLIwdgX",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2sqTHQq8rxsQQAyKi4jpNLIwdgX"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.8royv2agtwqkffq3.local-ngrok-cname.com",
			"created_at": "2025-02-10T10:06:56Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2sqTHRLNLZ1WIhKPAfELzULuh9f",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2sqTHRLNLZ1WIhKPAfELzULuh9f"
		},
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
					"started_at": "2025-02-10T10:06:56Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.8royv2agtwqkffq3.local-ngrok-cname.com",
			"created_at": "2025-02-10T10:06:56Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2sqTHR8VapAChk05Cdqs2PGNnzP",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2sqTHR8VapAChk05Cdqs2PGNnzP"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
