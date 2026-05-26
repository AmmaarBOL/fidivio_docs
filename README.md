# Fidivio Documentation

Product documentation for [Fidivio](https://www.fidivio.com) — the world's first off-the-shelf financial analysis tool dedicated to loyalty programs.

Built with [Mintlify](https://mintlify.com).

## Structure

Three top-level tabs:

| Tab | Purpose |
| --- | --- |
| **User Guide** | Task-oriented guides for setup, configuration, data upload, and troubleshooting |
| **Technical Memorandum** | Accounting methodology, configuration parameters, and calculation detail |
| **API Reference** | API documentation (in progress) |

```
├── docs.json
├── user-guide/
│   ├── getting-started/
│   ├── platform-navigation/
│   ├── program-setup/
│   ├── partner-management/
│   ├── user-role-management/
│   ├── data-input/
│   ├── data-categories/
│   ├── accounting-concepts/
│   ├── troubleshooting/
│   └── reference/
├── technical-memo/
│   ├── configuration/
│   ├── calculations/
│   └── background-*.mdx
└── api-reference/
```

## Local Development

Requires Node.js LTS (v22 or v24). Node 25+ is not supported by the Mintlify CLI.

```bash
nvm use 22
mint login    # one-time — enables search in local preview
mint dev
```

Open [http://localhost:3000](http://localhost:3000). If search shows "Login into CLI to enable search", run `mint login` and restart `mint dev`.

## Check for Broken Links

```bash
mint broken-links
```
