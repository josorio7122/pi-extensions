# pi-extensions

Collection of useful [pi](https://github.com/nickarino/pi-coding-agent) extensions.

## Extensions

| Extension | Description |
|-----------|-------------|
| [delete-session](packages/delete-session/) | Adds `/delete` to delete the current session |
| [exit](packages/exit/) | Adds `/exit` as an alias for `/quit` |

## Installation

Install all extensions at once from GitHub:

```bash
pi install git:github.com/josorio7122/pi-extensions
```

Or install selectively using package filtering:

```bash
# Only the delete-session extension
pi install git:github.com/josorio7122/pi-extensions --extensions "packages/delete-session/extensions"

# Only the exit extension
pi install git:github.com/josorio7122/pi-extensions --extensions "packages/exit/extensions"
```

## License

MIT
