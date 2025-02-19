## Shanghai Network Upgrade Specification

### Included EIPs
Specifies changes included in the Network Upgrade.

### EIPs Considered for Inclusion
Specifies changes potentially included in the Network Upgrade, pending successful deployment on Client Integration Testnets.

* [EIP-3540: EVM Object Format (EOF) v1](https://eips.ethereum.org/EIPS/eip-3540)
* [EIP-3651: Warm COINBASE](https://eips.ethereum.org/EIPS/eip-3651)
* [EIP-3670: EOF - Code Validation](https://eips.ethereum.org/EIPS/eip-3670)
* [EIP-3855: PUSH0 instruction](https://eips.ethereum.org/EIPS/eip-3855)
* [EIP-3860: Limit and meter initcode](https://eips.ethereum.org/EIPS/eip-3860)
* [EIP-4895: Beacon chain push withdrawals as operations](https://eips.ethereum.org/EIPS/eip-4895)

### Readiness Checklist

**List of outstanding items before deployment.**

Code merged into Participating Clients:

| EIP | [EIP-3540](https://eips.ethereum.org/EIPS/eip-3540) | [EIP-3670](https://eips.ethereum.org/EIPS/eip-3670) | [EIP-3855](https://eips.ethereum.org/EIPS/eip-3855) | [EIP-3860](https://eips.ethereum.org/EIPS/eip-3860) |
|------------------|------|------|------|------|
| **Geth**         | [Not merged](https://github.com/ethereum/go-ethereum/pull/22958) | [Not merged](https://github.com/ethereum/go-ethereum/pull/24090) | [Merged](https://github.com/ethereum/go-ethereum/pull/24039) | [Not merged](https://github.com/ethereum/go-ethereum/pull/23847) |
| **Besu**         | | | | |
| **Nethermind**   | | | | |
| **OpenEthereum** | | | | |
| **Erigon**    | | | | |
| **EthereumJS**   | | | [Merged](https://github.com/ethereumjs/ethereumjs-monorepo/pull/1616) | [Not merged](https://github.com/ethereumjs/ethereumjs-monorepo/pull/1619) |

 Tasks
- [ ] Client Integration Testing
  - [ ] Deploy a Client Integration Testnet
  - [ ] Integration Tests
  - [ ] Fuzz Testing
 - [ ] Select Fork Blocks
 - [ ] Deploy Clients
   - [ ]  Geth
   - [ ]  Besu
   - [ ]  Nethermind
   - [ ]  OpenEthereum
   - [ ]  Erigon
   - [ ]  EthereumJS
 - [ ] Pass Fork Blocks
