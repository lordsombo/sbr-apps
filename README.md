# apps

A Stable collection of signed downloadable apps, distributed as self-contained `.sbr` packages.

Each `.sbr` is a single, ready-to-run binary — download one and install it with your app client.

## Catalog

| App | What it is |
|-----|-----------|
| `canvas` | Signed first-party layered drawing and image editing |
| `cipher` | Signed first-party hashing, text encoding, and authenticated sealing utility |
| `comms` | Signed first-party live chat with durable conversation cache and offline fallback |
| `logbook` | Signed first-party notes with persistent search, import, and export |
| `navcomp` | Signed first-party Mapbox map with pan, zoom, and a bounded persistent tile cache |
| `navigator` | Signed first-party browser with HTML, CSS, JavaScript, images, and tabs |
| `tazama` | Signed first-party local video and audio player with multiple sources and persistent lists |
| `uplink` | Signed first-party mail client with compose and durable offline cache |
| `vault` | Signed first-party encrypted password store with authenticated recovery export |

## Labs

Unsigned SDK examples are isolated under [`labs/`](labs/README.md). They are not entries in this
Stable catalog and Forge's trusted transaction must not offer them as Stable products.

## Install

Use Forge in Sibuor to discover and install these Stable packages. Package authors build, inspect,
sign, and verify releases through the public `mw` command; the repository itself contains no
private signing keys.
