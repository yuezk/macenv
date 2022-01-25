# macenv
Set environment variables for GUI applications in macOS.

## Install/Update

```bash
curl -L https://raw.githubusercontent.com/yuezk/macenv/main/macenv > $HOME/.macenv && chmod +x $HOME/.macenv
```

## Usage

```bash
~/.macenv set JAVA_HOME /path/to/java/home
```

Then relaunch your GUI apps to make them aware. For command line apps, launch a new Terminal session.

**NOTE: The environment variables set by this tool will be persisted during OS restarting. If you found it doesn’t take effect after the OS restarts, please try to relaunch your GUI applications because there is some delay before the environment variables take effect.**

View the available options with `~/.macenv --help`.

## Uninstall

```
~/.macenv --uninstall
rm -rf ~/.macenv
```

## LICENSE

[MIT License](./LICENSE)
