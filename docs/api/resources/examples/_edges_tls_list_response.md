<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-05-18T10:05:00Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2xGS1Gkc83D7euneItSQQIQ7gFn",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xGS1Gkc83D7euneItSQQIQ7gFn"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2xGRzu9b3BgASlpkeoWPwplKRAn",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2xGRzu9b3BgASlpkeoWPwplKRAn"
        },
        "enabled": true
      },
      "created_at": "2025-05-18T10:04:49Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2xGRzxEBYb463urNuSCL6mpLSGO",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xGRzxEBYb463urNuSCL6mpLSGO"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
