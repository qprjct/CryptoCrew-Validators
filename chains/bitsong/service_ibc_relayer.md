## CryptoCrew IBC relayer
IBC relayers play a crucial role in the interchain by efficiently managing and transmitting data and assets between different blockchain networks using the Inter-Blockchain Communication (IBC) protocol.

To facilitate interchain message transfers, CryptoCrew utilizes the following IBC relayer software: 
- <a href="https://github.com/informalsystems/hermes"><code>hermes (ibc-rust)</code></a> relayer by [Informal Systems](https://github.com/informalsystems)
- <a href="https://github.com/cosmos/relayer"><code>rly (ibc-go)</code></a> relayer by [Strangelove Ventures](https://github.com/strangelove-ventures)

Active Relayer Wallets:

- `bitsong1yvejj22t78s2vfk7slty2d7fs5lkc8rnlzr68n`

### Active IBC channels `bitsong`
| src_chain | dst_chain | IBC port | IBC channel |
| --------------- | --------------- | ------------ | ------------------- |
| bitsong-2b | osmosis-1 | transfer | channel-0 |
| bitsong-2b | cosmoshub-4 | transfer | channel-1 |
| bitsong-2b | juno-1 | transfer | channel-5 |
| cosmoshub-4 | bitsong-2b | transfer | channel-229 |
| juno-1 | bitsong-2b | transfer | channel-17 |
| osmosis-1 | bitsong-2b | transfer | channel-73 |