# Foundry Plugin (developer)

Skills for **building, testing, and deploying** with [Foundry](https://getfoundry.sh).

> **Agent cast / Anvil runtime** moved to [`foundry-agent-skills`](https://github.com/cyotee/foundry-agent-skills) (plugin id `foundry-agent`). Install that package for on-chain RPC interaction skills.

## Skills

### forge-testing

Write and run Solidity tests with Foundry (cheatcodes, assertions, patterns).

### forge-fuzz-testing

Property-based and invariant testing.

### forge-deployment

`forge create` / `forge script` deployment and verification patterns.

### forge-signing

Signing cheatcodes for tests (EIP-712, permits).

### foundry-project

Project layout, `foundry.toml`, dependencies, remappings.

### supersim

Local Superchain multi-L2 simulation.

## Install

Via [cyotee-claude-plugins](https://github.com/cyotee/cyotee-claude-plugins):

```bash
/plugin install foundry@cyotee
/plugin install foundry-agent@cyotee   # cast / anvil / agent safety
```

## License

MIT
