# STORED and VERIFIED

[**lastest**](https://euphoria.aurascan.io/code-ids/detail/1379)

[**v0.5.3**](https://euphoria.aurascan.io/code-ids/detail/1380)

# RUST-OPTIMIZER
```Javascript
docker run --rm -v "$(pwd)":/code \
  --mount type=volume,source="$(basename "$(pwd)")_cache",target=/target \
  --mount type=volume,source=registry_cache,target=/usr/local/cargo/registry \
  cosmwasm/rust-optimizer:0.13.0
```