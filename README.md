![gitui for Debian](.github/readme-header.png)

# gitui for Debian

[gitui-org/gitui](https://github.com/gitui-org/gitui) — Blazing fast terminal UI for git. —
packaged for Debian as part of [latest-debs](https://github.com/latest-debs).

## Install

Via the latest-debs apt repository:

```sh
sudo extrepo enable latest-debs
sudo apt update
sudo apt install gitui
```

Or download a `.deb` from the [Releases](https://github.com/latest-debs/gitui-debian/releases) page:

```sh
sudo dpkg -i gitui_*.deb
```

## Supported distributions & architectures

- Debian Bookworm (12), Trixie (13), Forky (14/testing), Sid (unstable)
- amd64, arm64, armhf, i386, ppc64el, riscv64, s390x — whichever
  architectures gitui-org/gitui actually publishes a Linux binary for

## Disclaimer

Unofficial packaging only. For issues with gitui itself, see
[gitui-org/gitui](https://github.com/gitui-org/gitui).
