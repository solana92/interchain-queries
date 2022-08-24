default_chain: STRIDE-TESTNET-4
chains:
  GAIA:
    key: gaia-icq
    chain-id: GAIA
    rpc-addr: http://138.201.139.207:21657
    grpc-addr: http://138.201.139.207:1090
    account-prefix: cosmos
    keyring-backend: test
    gas-adjustment: 1.2
    gas-prices: 1uatom
    key-directory: /root/.icq/keys
    debug: false
    timeout: 20s
    block-timeout: ""
    output-format: json
    sign-mode: direct
  STRIDE-TESTNET-4:
    key: stride-icq
    chain-id: STRIDE-TESTNET-4
    rpc-addr: http://localhost:26657
    grpc-addr: http://localhost:6060
    account-prefix: stride
    keyring-backend: test
    gas-adjustment: 1.2
    gas-prices: 1ustrd
    key-directory: /root/.icq/keys
    debug: false
    timeout: 20s
    block-timeout: ""
    output-format: json
    sign-mode: direct
cl: {}