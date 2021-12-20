## Export Fish variables

```fish
starship init fish | source

set -x STARSHIP_CONFIG ~/.config/starship/starship.toml
set -x STARSHIP_CACHE ~/.config/starship/cache
```

## Export Bash variables

```bash
eval "$(starship init bash)"

export STARSHIP_CONFIG=~/.config/starship/starship.toml
export STARSHIP_CONFIG=~/.config/starship/cache
```
---
## Preview
