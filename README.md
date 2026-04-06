# gc-test-tap

Test tap for [gc-packman](https://github.com/donbox/gc-packman) development.

Contains two minimal packs for exercising the full packman workflow:

- **alpha** — a minimal agent pack (greeter agent)
- **beta** — a formula-only pack (mol-hello)

## Tagged versions

```
alpha/v1.0.0
alpha/v1.1.0
alpha/v1.2.0
beta/v1.0.0
beta/v2.0.0
beta/v2.0.1
```

## Usage

```
gc packman tap add test-tap https://github.com/donbox/gc-test-tap
gc packman search alpha
gc packman add test-tap/alpha
gc packman add test-tap/beta --version "^2.0"
```
