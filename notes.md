node_modules/ipfs-utils/src/http.js:127
    return this.fetch(resource, { ...options, method: 'POST', duplex: 'half' })

0b350c8c7a16110d8d61c9a3c71c4c35cb39fc779787820fde8c291d06bfe55c0d75f913175fefd21161e6b6c7399cee2c4215016e07abd395ab3dc15856ecaa

➜  anchor git:(main) ✗ ipfs config --json API.HTTPHeaders.Access-Control-Allow-Origin \
  '["http://localhost:3000"]'

➜  anchor git:(main) ✗ ipfs config --json API.HTTPHeaders.Access-Control-Allow-Methods \
  '["GET","POST","PUT","OPTIONS"]'

➜  anchor git:(main) ✗ ipfs config --json API.HTTPHeaders.Access-Control-Allow-Credentials '["true"]'
ipfs config --json API.HTTPHeaders.Access-Control-Allow-Headers \
  '["Content-Type","Authorization"]'


    "pkg:proof_utils": "cd ./anchor/tests/proof_utils && cargo install wasm-pack && wasm-pack build --target bundler && cd -",

--target nodejs / web / bundler

1/ update the @dashboard-ui.tsx to go to /voucher for a particular election and where the input can paste the secret in hex
2/ /voucher @voucher.ui.tsx should take the url param to facilite downloading a voucher for one election at a time

ipfs config --json API.HTTPHeaders.Access-Control-Allow-Origin \
  '["http://localhost:3000"]'


ipfs config --json API.HTTPHeaders.Access-Control-Allow-Origin \
  '["https://cloak-minster-ballot.rippner.com"]'


➜  anchor git:(main) ✗ ipfs config --json API.HTTPHeaders.Access-Control-Allow-Methods \
  '["GET","POST","PUT","OPTIONS"]'

➜  anchor git:(main) ✗ ipfs config --json API.HTTPHeaders.Access-Control-Allow-Credentials '["true"]'
ipfs config --json API.HTTPHeaders.Access-Control-Allow-Headers \
  '["Content-Type","Authorization"]'

➜  anchor git:(main) ✗ ipfs daemon


b931a7756dcf03509403e296faee4b40f2afd7977ccc2a10b01b15974a587b4242dc7ea469c6c4d6d09cc459f94584eec10119297313dc0aa3bead9fb4cf4006

solana program close --buffers
