> Quick Import on Windows

```nushell
http get https://raw.githubusercontent.com/math-queiroz/dotfiles/refs/heads/main/nushell/config.nu | save -f ($env.APPDATA + /nushell/config.nu)
http get https://raw.githubusercontent.com/math-queiroz/dotfiles/refs/heads/main/nushell/env.nu | save -f ($env.APPDATA + /nushell/env.nu)
```
