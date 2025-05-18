<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-18T10:04:54Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2xGRzxtNRwn1QqUBoUbc0su7Onn",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xGRzxtNRwn1QqUBoUbc0su7Onn"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xGS0XTwbGeQ5bSavMDi4rltbxD",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-18T10:04:54Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2xGS0XTwbGeQ5bSavMDi4rltbxD",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-18T10:04:52Z",
      "hostport": "2614a85bdb8e.ngrok.paid:443",
      "id": "ep_2xGS0NfmYXvgfQAmm5pQSqgUFEy",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2xGRxwzozONqX2YiesCibzv4bk0",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://2614a85bdb8e.ngrok.paid",
      "tunnel": {
        "id": "tn_2xGS0NfmYXvgfQAmm5pQSqgUFEy",
        "uri": "https://api.ngrok.com/tunnels/tn_2xGS0NfmYXvgfQAmm5pQSqgUFEy"
      },
      "tunnel_session": {
        "id": "ts_2xGS0J2qHnAx8LONLkachZOPIQl",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2xGS0J2qHnAx8LONLkachZOPIQl"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-18T10:04:52Z",
      "upstream_url": "http://localhost:80",
      "url": "https://2614a85bdb8e.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-18T10:04:50Z",
      "domain": {
        "id": "rd_2xGRzxtNRwn1QqUBoUbc0su7Onn",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xGRzxtNRwn1QqUBoUbc0su7Onn"
      },
      "edge": {
        "id": "edgtls_2xGRzxEBYb463urNuSCL6mpLSGO",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2xGRzxEBYb463urNuSCL6mpLSGO"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xGRzvMtHts6KqPp6CedjXWVTl4",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-18T10:04:50Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
