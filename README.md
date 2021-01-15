# 🛡️ `security-headers-template` 🔒
Analyze Your HTTP Response Headers Here:
https://securityheaders.com/

This is a template for setting the proper security headers for your domain when using CloudFlare as your reverse DNS Proxy

[`index.js`](https://github.com/jamesta696/set-security-headers/blob/master/index.js) is the content of the Workers script.

#### Wrangler

To generate using [wrangler](https://github.com/cloudflare/wrangler)

#### Include your own `wrangler.toml` file

```
wrangler generate projectname https://github.com/jamesta696/set-security-headers
```

Further documentation for Wrangler can be found [here](https://developers.cloudflare.com/workers/tooling/wrangler).
