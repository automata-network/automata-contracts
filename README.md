# Automata Contracts

Follow the instructions below to add our contracts as dependencies to your project.

## Hardhat

Simply install the `@@automata-network/contracts` npm package, by running the command below:

```bash
yarn add @automata-network/contracts
```

## Foundry

Run the command below:

```bash
forge install automata-network/automata-contracts
```

After installing the dependency, it is recommended that you manually configure remappings in either `Foundry.toml` or `remappings.txt`.

```
@automata-network/contracts/=lib/automata-contracts/
```

---

Here's an example of importing `IAutomataVRFCoordinator.sol` into your project.

```solidity
import {IAutomataVRFCoordinator} from "@automata-network/contracts/vrf/IAutomataVRFCoordinator.sol";
```