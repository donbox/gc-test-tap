# gc-test-tap

Test tap for [gc-packman](https://github.com/donbox/gc-packman) development.

Contains two minimal packs for exercising the full packman workflow:

- **foo** — a minimal pack with an `about` command
- **bar** — a minimal pack with an `about` command

Each pack ships a single command (`gc foo about` / `gc bar about`) that prints its name, version, and tap.

## Tagged versions

```
foo/v1.0.0
foo/v1.1.0
foo/v1.2.0
bar/v1.0.0
bar/v2.0.0
bar/v2.0.1
```

## Usage

```
gc packman tap add test-tap https://github.com/donbox/gc-test-tap
gc packman search foo
gc packman add test-tap/foo
gc packman add test-tap/bar --version "^2.0"
```
