## CryptoCrew IBC relayer
IBC relayers play a crucial role in the interchain by efficiently managing and transmitting data and assets between different blockchain networks using the Inter-Blockchain Communication (IBC) protocol.

To facilitate interchain message transfers, CryptoCrew utilizes the following IBC relayer software: 
- <a href="https://github.com/informalsystems/hermes"><code>hermes (ibc-rust)</code></a> relayer by [Informal Systems](https://github.com/informalsystems)
- <a href="https://github.com/cosmos/relayer"><code>rly (ibc-go)</code></a> relayer by [Strangelove Ventures](https://github.com/strangelove-ventures)

Active Relayer Wallets:

- `gravity1yvejj22t78s2vfk7slty2d7fs5lkc8rnhmr2q5`
- `gravity15md2qvgma8lnvqv67w0umu2paqkqkhega6t5dh`

### Active IBC channels `gravitybridge`
| src_chain | dst_chain | IBC port | IBC channel |
| --------------- | --------------- | ------------ | ------------------- |
| gravity-bridge-3 | secret-4 | transfer | channel-79 |
| gravity-bridge-3 | comdex-1 | transfer | channel-112 |
| gravity-bridge-3 | core-1 | transfer | channel-24 |
| gravity-bridge-3 | osmosis-1 | transfer | channel-10 |
| gravity-bridge-3 | comdex-1 | transfer | channel-21 |
| gravity-bridge-3 | kaiyo-1 | transfer | channel-83 |
| cosmoshub-4 | gravity-bridge-3 | transfer | channel-281 |
| juno-1 | gravity-bridge-3 | transfer | channel-31 |
| osmosis-1 | gravity-bridge-3 | transfer | channel-144 |
| secret-4 | gravity-bridge-3 | transfer | channel-17 |
| core-1 | gravity-bridge-3 | transfer | channel-38 |
| comdex-1 | gravity-bridge-3 | transfer | channel-23 |
| evmos_9001-2 | gravity-bridge-3 | transfer | channel-8 |
| kaiyo-1 | gravity-bridge-3 | transfer | channel-11 |
| osmosis-1 | gravity-bridge-3 | transfer | channel-144 |