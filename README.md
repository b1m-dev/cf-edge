# cf-node
Determine which Cloudflare edge location you are connected to.

/worker is a template for a JavaScript Worker in Cloudflare, due to CORS, you
can only test against your own Worker (unless security settings permit)

/powershell does the same, but as it doesn't observe CORS you can use it
against any website proxied by Cloudflare
