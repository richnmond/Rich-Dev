## GitHub Copilot Chat

- Extension Version: 0.24.1 (prod)
- VS Code: vscode/1.97.2
- OS: Windows

## Network

User Settings:
```json
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 140.82.121.5 (743 ms)
- DNS ipv6 Lookup: Error (588 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (34 ms)
- Electron fetch (configured): HTTP 200 (1995 ms)
- Node.js https: HTTP 200 (961 ms)
- Node.js fetch: HTTP 200 (722 ms)
- Helix fetch: 