# libffi

libffi 3.4.6 foreign function interface library (closures use plain executable memory)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install libffi
```

| | |
|---|---|
| Version | 3.4.6 |
| Licence | MIT |
| Upstream | https://sourceware.org/libffi/ |
| Needs | [`gcc`](https://github.com/Artfical/tpkg-gcc) |
| Needs tOS build | 615 or newer |
| Size | 67796 bytes (181803 unpacked) |
| SHA-256 of the `.tpkg` | `190aeabcfcc70a0346689d1752d07c64939132019ccf6adffa3154086c586caa` |

## Commands it adds

| Command | Runs |
|---|---|
| - | - |

## Download

The package file (`libffi-3.4.6.tpkg`) and the sources it was built from are the assets of the
[v3.4.6 release](https://github.com/Artfical/tpkg-libffi/releases/tag/v3.4.6).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `libffi-3.4.6.tar.gz`

Check a download: `sha256sum libffi-3.4.6.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: MIT. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
