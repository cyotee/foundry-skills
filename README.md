# Foundry Plugin

Skills with progressive disclosure for using [Foundry](https://getfoundry.sh) - the blazing fast Ethereum development toolkit.

## Overview

This plugin provides comprehensive skills for all core Foundry tools:

- **Forge** - Build, test, fuzz, debug, and deploy Solidity contracts
- **Cast** - Swiss Army knife for interacting with EVM chains
- **Anvil** - Fast local Ethereum development node

## Skills

### forge-testing

Write and run Solidity tests with Foundry. Covers test structure, assertions, cheatcodes, and running tests.

**Use when:**
- Writing unit tests for smart contracts
- Testing access control and permissions
- Verifying event emissions
- Testing revert conditions

**Files:**
- `SKILL.md` - Main skill with quick start and essential cheatcodes
- `cheatcodes.md` - Complete cheatcode reference (vm.prank, vm.deal, vm.warp, etc.)
- `assertions.md` - All assertion functions (assertEq, assertGt, assertApproxEqAbs, etc.)
- `patterns.md` - Common testing patterns and best practices

### forge-fuzz-testing

Property-based testing with Foundry's fuzzer. Covers fuzz test structure, input constraints, fixtures, and invariant testing.

**Use when:**
- Testing mathematical operations for edge cases
- Finding unexpected inputs that break invariants
- Security testing for unexpected behaviors

**Files:**
- `SKILL.md` - Fuzz testing basics, constraints, and configuration
- `invariants.md` - Comprehensive invariant testing patterns with handlers and ghost variables

### forge-deployment

Deploy and verify smart contracts with Foundry. Covers deployment scripts, verification, and multi-chain deployments.

**Use when:**
- Deploying contracts to testnets or mainnet
- Writing deployment scripts in Solidity
- Verifying contracts on Etherscan/Sourcify
- Managing multi-chain deployments

**Files:**
- `SKILL.md` - Quick deploy with forge create and script basics
- `scripts.md` - Comprehensive Solidity script patterns
- `multichain.md` - Multi-chain deployment strategies

### cast-commands

Interact with EVM chains using Cast CLI. The Swiss Army knife for chain interaction.

**Use when:**
- Querying contract state (balances, storage, call results)
- Sending transactions
- Converting between data formats
- Debugging transactions

**Files:**
- `SKILL.md` - Core Cast commands reference
- `patterns.md` - Common Cast recipes and scripting patterns

### anvil-node

Run local Ethereum nodes with Anvil for development and testing.

**Use when:**
- Local development and testing
- Forking mainnet or other networks
- Integration testing with frontend applications

**Files:**
- `SKILL.md` - Anvil setup, configuration, and RPC methods
- `forking.md` - Detailed forking patterns (impersonation, time travel, snapshots)

### foundry-project

Set up and configure Foundry projects.

**Use when:**
- Creating new Foundry projects
- Configuring foundry.toml settings
- Managing dependencies
- Setting up remappings

**Files:**
- `SKILL.md` - Project structure, dependencies, and common tasks
- `config.md` - Complete foundry.toml configuration reference

## Installation

Add this plugin to your Claude Code plugins:

```bash
# In your plugins directory
git submodule add https://github.com/your-org/foundry-plugin plugins/foundry
```

## Compatibility

- **Claude Code**: Full support via `.claude-plugin/`
- **OpenCode**: Full support via `.opencode/` symlinks

## Resources

- [Foundry Documentation](https://getfoundry.sh)
- [Foundry GitHub](https://github.com/foundry-rs/foundry)
- [Foundry Book](https://book.getfoundry.sh)

## License

MIT
