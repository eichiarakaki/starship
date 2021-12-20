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

![2021-12-20_13-15](https://user-images.githubusercontent.com/73294642/146711460-1964dc0f-5075-4085-8dd8-d2e1f23dd5fd.png)

![2021-12-20_13-16](https://user-images.githubusercontent.com/73294642/146711473-3dd491dc-2b62-4a50-9e52-a005c3627e08.png)
