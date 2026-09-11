# dirdust

Go CLI that organizes a messy folder by file extension

Built for my own use; public in case it helps someone.

## Highlights

- Single static binary, no runtime deps
- Dry-run prints the plan before moving anything
- Skips hidden files and folders by default
- Groups files into folders by extension

## Getting started

```bash
go build -o bin/ ./...
```

## Examples

```bash
./bin/dirdust ~/Downloads --dry-run
./bin/dirdust ~/Downloads
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```

## License

MIT - see [LICENSE](LICENSE).
