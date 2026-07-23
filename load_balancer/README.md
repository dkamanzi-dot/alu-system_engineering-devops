# Load Balancer

This project sets up redundancy for the web infrastructure by adding a second web server and configuring a load balancer using HAProxy to distribute traffic between them using a round-robin algorithm.

## Tasks

- **0-custom_http_response_header** — Bash script that installs Nginx and configures a custom HTTP response header `X-Served-By`, set to the server's hostname, so we can track which web server handled a given request.
- **1-install_load_balancer** — Bash script that installs and configures HAProxy on the load balancer server to distribute traffic between web-01 and web-02 using round-robin.

## Requirements

- All scripts start with `#!/usr/bin/env bash`
- Each script includes a comment describing its purpose
- Scripts are executable and run without human intervention
- Scripts pass Shellcheck without errors (SC2154 ignored where noted)
