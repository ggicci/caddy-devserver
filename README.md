# caddy-devserver

Automate local HTTPS development domains with Caddy.

## Usage

```
Usage: caddy-devserver <enable|disable> [FILE]

Automate local HTTPS development domains with Caddy.

EXAMPLE

     caddy-devserver enable # interactively with fzf
     caddy-devserver enable ./myapp.localhost.Caddyfile
     caddy-devserver enable /path/to/myapp.localhost.Caddyfile

     caddy-devserver disable # interactively with fzf
     caddy-devserver disable myapp.localhost
     caddy-devserver disable ./myapp.localhost.Caddyfile
     caddy-devserver disable /path/to/myapp.localhost.Caddyfile
```
