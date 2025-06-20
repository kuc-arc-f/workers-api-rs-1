# workers-rs-4

 Version: 0.9.1

 date    : 2025/06/20 

 update :

***

Cloudflare Workers + Rust API , example

***
* wrangler.toml

```
name = "workers-rs-2"
main = "build/worker/shim.mjs"
compatibility_date = "2023-03-22"
nodejs_compat = true

[build]
command = "cargo install -q worker-build && worker-build --release"

[[d1_databases]]
binding = "DB"
database_name = "db123"
database_id = ""

```
***
* dev-start


* cargo
```
cargo build
```
* npm install
```
npm i
npm run dev
```


***
### Blog

***


