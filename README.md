# cf-edge
Determine which Cloudflare edge location you are connected to.

[worker](https://github.com/b1m-dev/cf-node/blob/main/worker) is a template for a JavaScript Worker in Cloudflare.  Due to CORS, you can only test against your own Worker (unless security settings permit).

[powershell](https://github.com/b1m-dev/cf-node/blob/main/powershell) does the same, but as it doesn't observe CORS you can use it against any website proxied by Cloudflare.
