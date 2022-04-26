# Iyaxios

This module change the default node.js fingerprint to bypass some TLS Fingerprinting bot detections.

`npm i iyaxios`

# Note

you can use proxy with Https-proxy-agent, do not try the default proxy option. Be careful to keep in https setup instead of http

```js
const request = await axios.get('url' {
    httpsAgent: new HttpsProxyAgent(process.env.PROXY),
})
```

See https://github.com/axios/axios for usage
