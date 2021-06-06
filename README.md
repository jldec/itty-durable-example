# itty-durable Example

Forked from [kwhitley/itty-durable-example](https://github.com/kwhitley/itty-durable-example) on June 6, 2021.

Requires [wrangler >= v1.17.0](https://github.com/cloudflare/wrangler/releases) (doesn't install wrangler from npm.)

Updated build section of wrangler.toml per [docs](https://developers.cloudflare.com/workers/cli-wrangler/configuration#build).

NOTE: This code is currently broken - published worker returns error.

- `npm install`
- `wrangler publish --new-class Counter` (first time publishing)
- `wrangler publish`
