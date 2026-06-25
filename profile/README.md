# VulpineOS

```bash
curl -fsSL https://vulpineos.com/install | bash
vulpineos
```

VulpineOS is the open-source runtime for AI browser agents that need to operate on the real web.

It combines a Vulpine-branded Firefox browser, terminal-first agent runtime,
identity management, MCP tooling, a served web panel, and self-hosted
infrastructure for running browser agents locally or on your own servers.

## Open Source Runtime

- Browser-engine patches for safer agent execution
- Injection-resistant accessibility filtering
- Action-locking so pages stay stable while agents think
- Token-optimized DOM snapshots
- Go runtime, TUI, orchestrator, context pool, and identity vault
- MCP tools, Foxbridge CDP proxy, scripting, webhooks, cost tracking, and session recording

## Commands

```bash
vulpineos
vulpineos serve --host 0.0.0.0 --port 8443 --no-tls --api-key KEY
vulpineos remote --url http://host:8443 --api-key KEY
vulpineos mcp
```

## Repositories

- Runtime: https://github.com/VulpineOS/VulpineOS
- Docs: https://github.com/VulpineOS/vulpineos-docs
- Foxbridge: https://github.com/VulpineOS/foxbridge
- Vulpine Mark: https://github.com/VulpineOS/vulpine-mark
- MobileBridge for Android: https://github.com/VulpineOS/mobilebridge

## Links

- Repository: https://github.com/VulpineOS/VulpineOS
- Documentation: https://docs.vulpineos.com
- Website: https://vulpineos.com
- Install script: https://vulpineos.com/install

## License

The VulpineOS open-source runtime is released under the MPL 2.0 license.
