# Web Server

This project covers the basics of configuring a web server using Nginx, including installing Nginx, transferring files via `scp`, setting up redirects, and creating a custom 404 error page.

## Tasks

- **0-transfer_file** — Bash script that transfers a file to a remote server using `scp`, with strict host key checking disabled.
- **1-install_nginx_web_server** — Bash script that installs and configures Nginx to serve a page containing "Holberton School" at the root (`/`).
- **2-setup_a_domain_name** — Domain name configured with a DNS A record pointing to the web-01 server.
- **3-redirection** — Bash script that installs Nginx and configures a 301 redirect from `/redirect_me` to another URL.
- **4-not_found_page_404** — Bash script that installs Nginx, configures the redirect, and serves a custom 404 page containing the string "Ceci n'est pas une page".
- **5-design_a_beautiful_404_page.html** — A custom-designed 404 error page.

## Requirements

- All scripts start with `#!/usr/bin/env bash`
- Each script includes a comment describing its purpose
- Scripts are executable and run without human intervention
- `systemctl` is not used; `service` is used instead to restart Nginx
