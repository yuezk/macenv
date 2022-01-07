# macenv
Set environment variables for GUI applications in macOS.

## Install

```bash
curl -L https://raw.githubusercontent.com/yuezk/macenv/main/macenv > $HOME/.macenv && chmod +x $HOME/.macenv
```

## Usage

View the available options with `~/.macenv --help`.

```bash
~/.macenv set JAVA_HOME /path/to/java/home
```

Then relaunch your GUI apps to make them aware. For command line apps, launch a new Terminal session.

## Uninstall

```
./macenv --uninstall
```

## LICENSE

[MIT License](./LICENSE)
