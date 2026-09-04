# Omarchy Tailscale Widget

Standalone snapshot of the native Tailscale bar widget for Omarchy.

It provides connection status, connection switching, machine browsing, copy
actions, and Taildrop sending/receiving. The widget needs the `tailscale` CLI
and `wl-copy`; enable it in Omarchy as `omarchy.tailscale`.

The `examples/shell.json` file shows a minimal generic bar configuration. It
contains no machine names, tailnet names, IP addresses, usernames, or local
paths. The implementation and tests are based on Omarchy and retain its MIT
license in `LICENSE`.

## Files

- `shell/plugins/panels/tailscale/`: plugin files for Omarchy.
- `omarchy-tailscale-receive`: Taildrop receive helper.
- `test/shell.d/`: parser and receive-flow tests plus their small harness.
- `examples/shell.json`: generic bar placement example.
