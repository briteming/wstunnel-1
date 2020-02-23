# wstunnel

Tunnel IP over websocket.

Try [a modified version of JSLinux](https://jslinux.invariant.me) to see how it works. Notice the browser's dev-console as required network configuration will be printed there.

## Server usage

```
$ cargo install wstunnel
$ wstunnel --help
wstunnel 0.1.0
WebSocket layer 3 tunnel with authentication

USAGE:
    wstunnel [OPTIONS] --config <config> --listen <listen>

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
    -c, --config <config>    Path to config file
    -l, --listen <listen>    Listen address
    -t, --tun <tun>          Name of the local TUN device to use
```

An example config file is available at `test_config.toml`.