# Sobrio theme

![Screenshot](./.github/window.png)
_Typical Alacritty screen using this theme_

## About this theme

This is a theme for Alacritty, the terminal emulator. It uses the colors from the Sobrio theme to make your experience more unique.

## Installation

```yaml
# Sobrio colors for Alacrity Terminal
# Author: Elves Sousa <elvessousa.com.br>
# Copy or append these values to your alacritty.yml file
sobrio: &sobrio # Default colors
  primary:
    background: '#202020'
    foreground: '#eeeeee'

  # Normal colors
  normal:
    black: '#3a3b3f'
    red: '#fd6389'
    green: '#2ec27e'
    yellow: '#d7af87'
    blue: '#d7af87'
    magenta: '#d7d7ff'
    cyan: '#78dce8'
    white: '#eeeeee'

  # Bright colors
  bright:
    black: '#727072'
    red: '#fd6399'
    green: '#2ec27e'
    yellow: '#d7af10'
    blue: '#d7af10'
    magenta: '#d7d7ff'
    cyan: '#7cdce7'
    white: '#ffffff'

# Sobrio light colors for Alacrity Terminal
# Author: Elves Sousa <elvessousa.com.br>
# Copy or append these values to your alacritty.yml file
sobrio-light: &sobrio-light # Default colors
  primary:
    background: '#eeeeee'
    foreground: '#202020'

  # Normal colors
  normal:
    black: '#eeeeee'
    red: '#dd4c4f'
    green: '#2ec27e'
    yellow: '#af875f'
    blue: '#af875f'
    magenta: '#9787af'
    cyan: '#5fafaf'
    white: '#3a3b3f'

  # Bright colors
  bright:
    black: '#727072'
    red: '#fd6399'
    green: '#2ec27e'
    yellow: '#d7af87'
    blue: '#d7af87'
    magenta: '#d7d7ff'
    cyan: '#7cdce7'
    white: '#ffffff'
```

The "installation" process is quite simple. With the code above, just follow these four simple steps:

1. Copy the contents of the code you just saw to your `alacritty.yml`, usually found in `~/.config/alacritty/alacritty.yml`.
2. Add the line `colors: *sobrio` or `colors: *sobrio-light` and save the file.
3. ???
4. Profit!

![Screenshot](./.github/window-light.png)
_Light version_
