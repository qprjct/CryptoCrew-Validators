## CryptoCrew IBC relayer
IBC relayers play a crucial role in the interchain by efficiently managing and transmitting data and assets between different blockchain networks using the Inter-Blockchain Communication (IBC) protocol.

To facilitate interchain message transfers, CryptoCrew utilizes the following IBC relayer software: 
- <a href="https://github.com/informalsystems/hermes"><code>hermes (ibc-rust)</code></a> relayer by [Informal Systems](https://github.com/informalsystems)
- <a href="https://github.com/cosmos/relayer"><code>rly (ibc-go)</code></a> relayer by [Strangelove Ventures](https://github.com/strangelove-ventures)

Active Relayer Wallets:

- `terra1yvejj22t78s2vfk7slty2d7fs5lkc8rn40tj8u`

### Active IBC channels `terra2`
| src_chain | dst_chain | IBC port | IBC channel |
| --------------- | --------------- | ------------ | ------------------- |
| phoenix-1 | cosmoshub-4 | transfer | channel-0 |
| phoenix-1 | osmosis-1 | transfer | channel-1 |
| phoenix-1 | kaiyo-1 | transfer | channel-10 |
| phoenix-1 | juno-1 | transfer | channel-2 |
| phoenix-1 | secret-4 | transfer | channel-3 |
| phoenix-1 | osmosis-1 | wasm.terra1d90p5lacfxnqgjxjupu234lxnxyeu8fdeef4d0e0nqy3p30r7gss4myn9x | channel-85 |
| phoenix-1 | migaloo-1 | transfer | channel-86 |
| phoenix-1 | migaloo-1 | wasm.terra1e0mrzy8077druuu42vs0hu7ugguade0cj65dgtauyaw4gsl4kv0qtdf2au | channel-87 |
| cosmoshub-4 | phoenix-1 | transfer | channel-339 |
| juno-1 | phoenix-1 | transfer | channel-86 |
| kaiyo-1 | phoenix-1 | transfer | channel-5 |
| migaloo-1 | phoenix-1 | transfer | channel-0 |
| migaloo-1 | phoenix-1 | transfer | channel-2 |
| osmosis-1 | phoenix-1 | transfer | channel-251 |
| osmosis-1 | phoenix-1 | transfer | channel-559 |
| secret-4 | phoenix-1 | transfer | channel-16 |