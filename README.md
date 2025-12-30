# all.el

Edit all lines matching a given regexp.

## Overview

`all.el` provides a powerful way to simultaneously view and edit all lines in a buffer that match a regular expression. This is particularly useful for making bulk changes to specific patterns across your file.

Originally written by Per Abrahamsen, now maintained by Naoya Yamashita.

## Installation

### Package.el

```elisp
M-x package-install RET all RET
```

### Manual Installation

Download `all.el` and add it to your load path:

```elisp
(add-to-list 'load-path "/path/to/all.el")
(require 'all)
```

## Usage

Run the main command:

```
M-x all
```

You will be prompted for a regular expression. A new buffer will open showing all matching lines from the current buffer. Edit these lines as needed, and your changes will be reflected in the original buffer.

## License

GPL-3.0. See [LICENSE](LICENSE) for details.

## Contributing

Contributions are welcome. Please open an issue or submit a pull request on [GitHub](https://github.com/conao3/all.el).
