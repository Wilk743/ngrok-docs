<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2xGRxywZJhhhMLs8Q3QpmP6bcle",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2xGRxywZJhhhMLs8Q3QpmP6bcle"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.doxaqafxkg6iethm.local-ngrok-cname.com",
      "created_at": "2025-05-18T10:04:33Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2xGRy4Zj0BKjCJCx4l4fu1NNQsK",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2xGRy4Zj0BKjCJCx4l4fu1NNQsK"
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
          "started_at": "2025-05-18T10:04:34Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.doxaqafxkg6iethm.local-ngrok-cname.com",
      "created_at": "2025-05-18T10:04:34Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2xGRy3L5aKbys3Kqb5Kg7COOM5V",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2xGRy3L5aKbys3Kqb5Kg7COOM5V"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
