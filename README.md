## Kaspar Tomson

Founder of **[Maskbreak](https://maskbreak.com)** — a real-time fraud detection
API that flags VPNs, residential proxies, antidetect browsers and automated
traffic in under 40 ms.

Based in Tallinn, Estonia.

### What I'm building

Fraud tooling built around IP reputation misses most of what actually matters
now: rented residential proxies, spoofed browser fingerprints from
Kameleo/GoLogin/AdsPower, and agentic automation. Maskbreak pairs network
attribution with device fingerprinting so a single `POST /v1/evaluate` returns
an `allow` / `review` / `block` decision fast enough to sit in a checkout or
signup path.

Runs on Node.js and Express behind Cloudflare, with an edge worker handling the
first-pass scan and libSQL for storage.

### Open source

Official SDKs, all zero-dependency and MIT licensed:

| | Repository | Package |
|---|---|---|
| Node.js | [maskbreak-node](https://github.com/sentinelsup/maskbreak-node) | [`@sentinelsup/sdk`](https://www.npmjs.com/package/@sentinelsup/sdk) |
| Python | [maskbreak-python](https://github.com/sentinelsup/maskbreak-python) | [`sentinelsup`](https://pypi.org/project/sentinelsup/) |
| PHP | [maskbreak-php](https://github.com/sentinelsup/maskbreak-php) | [`sentinelsup/sdk`](https://packagist.org/packages/sentinelsup/sdk) |

### Elsewhere

[maskbreak.com](https://maskbreak.com) ·
[API docs](https://maskbreak.com/api) ·
[Blog](https://maskbreak.com/blog) ·
[@MaskbreakSup](https://x.com/MaskbreakSup) ·
[support@maskbreak.com](mailto:support@maskbreak.com)
