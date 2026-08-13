# picoCTF Write-ups

A growing collection of my solutions and notes for [picoCTF](https://picoctf.org/) challenges. Each write-up documents the reasoning, commands, and techniques used to reach the solution so the repository can serve as both a reference and a learning log.

> [!WARNING]
> These write-ups contain spoilers and flags. Try each challenge yourself before reading the solution.

## Progress

| Category | Solved |
| --- | ---: |
| Cryptography | 1 |
| **Total** | **1** |

Browse the complete [challenge index](CTF/README.md).

## Repository structure

```text
PICOCTF/
|-- CTF/
|   |-- README.md                    # Challenge index
|   `-- Cryptography/
|       `-- interencdec/
|           |-- README.md            # Challenge write-up
|           `-- assets/              # Images and supporting files
|-- WRITEUP_TEMPLATE.md              # Template for future solutions
`-- README.md
```

Each challenge gets its own folder. This keeps screenshots, scripts, downloads, and notes together without cluttering the repository root.

## Adding a new solution

1. Copy `WRITEUP_TEMPLATE.md` into `CTF/<Category>/<challenge-name>/README.md`.
2. Put screenshots and small supporting files in that challenge's `assets/` folder.
3. Add the challenge to `CTF/README.md` and update the totals above.
4. Use a short commit message such as `Add vault-door-training write-up`.

## Disclaimer

This repository is for education and authorized CTF practice only. Challenge names and materials belong to their respective owners.
