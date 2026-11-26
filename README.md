# Bubbles Wire&trade;

The private wire of the Bubbles stack.

Bubbles Wire&trade; is a self-hosted private networking layer that links your
machines into one encrypted fabric: nodes register with your own hub, channels
are brokered peer-to-peer or spliced through your own relay, and forwarded
listeners let any TCP service ride the fabric. Identity keys are generated on
each device and never leave it — there is no third-party control plane.

- Hub / relay / node architecture — you run all of it
- Per-channel mutual key verification with pinned peer files
- TCP forwarding through brokered channels (`fwd`, `ssh` shortcut)
- Windows, Linux, and macOS (Apple Silicon) targets
- Written in BUB, compiled by the bubbles_native toolchain

Part of the Bubbles family: **BubblesOS** (OS) / **BubblesForge** (dev suite) /
**Bubbles Wire** (networking) / **VirPort** (portal).

> Bubbles Wire is a trademark of the project author. Source will be published
> under a license to be determined.

---
*First public notice: November 25, 2026.*
