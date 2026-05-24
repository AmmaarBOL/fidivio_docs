# Fidivio Documentation

Product documentation for [Fidivio](https://www.fidivio.com) — the world's first off-the-shelf financial analysis tool dedicated to loyalty programs.

Built with [Mintlify](https://mintlify.com).

## Structure

```
├── docs.json                  # Mintlify configuration
├── user-guide/                # User Guide (Tab 1)
│   ├── introduction.mdx
│   ├── getting-started.mdx
│   ├── platform-navigation.mdx
│   ├── program-setup.mdx
│   ├── partner-management.mdx
│   ├── user-role-management.mdx
│   └── data-input.mdx
├── technical-memo/            # Technical Memorandum (Tab 2)
│   ├── introduction.mdx
│   ├── change-control.mdx
│   ├── components.mdx
│   ├── configuration.mdx
│   ├── inputs.mdx
│   ├── calculations-outputs.mdx
│   ├── configuration-effects-summary.mdx
│   ├── accounting-definitions.mdx
│   ├── background-ssp.mdx
│   ├── background-contract-liability.mdx
│   ├── background-marketing-income.mdx
│   ├── background-breakage-income.mdx
│   └── miscellaneous.mdx
└── api-reference/             # API Reference (Tab 3)
    └── overview.mdx
```

## Local Development

```bash
npx mintlify dev
```

## Check for Broken Links

```bash
npx mintlify broken-links
```
