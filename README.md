### Description

Rust prover for webproofs for action flow based on zkNotary

### Commands
- Make proof for transaction inclusion for autotrading 
`cargo run --release --example simple_prover -- "sepolia.optimism.io" "/" "POST" '{"method":"eth_getTransactionByHash","params":["0x5a34d74b17fc7af7da4b9ca3dc2b03ef4a38d24d0525017e904faac541cc8c44"],"id":1,"jsonrpc":"2.0"}' ''`

- Make bullish twitter post proof
`cargo run --release --example simple_prover -- "api.x.com" "/2/tweets/1857425028305879466" "GET" '' 'Bearer AAAAAAAAAAAAAAAAAAAAAAUFxAEAAAAAXOIYoqCogVfV6URHTSrKz%2Bya5zA%3DBNcfTrtNepUdCu9uVMADV0QtseBdoSDiCHaOFM7vkjE4tOiEuy'`