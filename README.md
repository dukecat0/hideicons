# hideicons

Display or hide the desktop icons from the command line on macOS.

## Installation

Using homebrew:

```
brew tap meowmeowmeowcat/taps
brew install meowmeowmeowcat/taps/hideicons
```

Install manually:
```
curl -L https://raw.githubusercontent.com/meowmeowmeowcat/hideicons/main/hideicons \
 -o /usr/local/bin/hideicons && chmod +x /usr/local/bin/hideicons
```

## Example

If your desktop icons are not hidden:
```
$ hideicons
Desktop icons are hidden!
```

If your desktops icons are hidden:
```
$ hideicons
Desktop icons are shown!
```

