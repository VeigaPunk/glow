<!-- veigapunk-upstream-maintainers:start -->
> **Upstream package maintainer contact(s):** [Christian Muehlhaeuser (`muesli`)](https://github.com/muesli). Declared in the upstream release configuration.

<details><summary>All contributors (52)</summary>

- Christian Rocha ([`meowgorithm`](https://github.com/meowgorithm))
- Christian Muehlhaeuser ([`muesli`](https://github.com/muesli))
- dependabot\[bot\] ([`dependabot[bot]`](https://github.com/dependabot%5Bbot%5D))
- Carlos Alexandro Becker ([`caarlos0`](https://github.com/caarlos0))
- Nicolas M\. ([`penguwin`](https://github.com/penguwin))
- Andrey Nering ([`andreynering`](https://github.com/andreynering))
- Toby Padilla ([`toby`](https://github.com/toby))
- Ayman Bagabas ([`aymanbagabas`](https://github.com/aymanbagabas))
- Toby Padilla
- Charm ([`charmcli`](https://github.com/charmcli))
- Maas Lalani ([`maaslalani`](https://github.com/maaslalani))
- bashbunni ([`bashbunni`](https://github.com/bashbunni))
- Shane\-XB\-Qian ([`Shane-XB-Qian`](https://github.com/Shane-XB-Qian))
- github\-actions\[bot\] ([`github-actions[bot]`](https://github.com/github-actions%5Bbot%5D))
- Markus Billharz ([`MarkusBillharz`](https://github.com/MarkusBillharz))
- Ktrod ([`Ktrod`](https://github.com/Ktrod))
- Aitva ([`aitva`](https://github.com/aitva))
- Prashanta Paudel ([`pacificpaudel`](https://github.com/pacificpaudel))
- Prithvi Jethwa ([`prithvijj`](https://github.com/prithvijj))
- Sebastian Cohnen ([`tisba`](https://github.com/tisba))
- Selwyn ([`Siilwyn`](https://github.com/Siilwyn))
- Stanislav \(Stas\) Katkov ([`skatkov`](https://github.com/skatkov))
- Tobias Klauser ([`tklauser`](https://github.com/tklauser))
- WieeRd ([`WieeRd`](https://github.com/WieeRd))
- Jinglue ([`batkiz`](https://github.com/batkiz))
- bubersson ([`bubersson`](https://github.com/bubersson))
- borbitter ([`haennes`](https://github.com/haennes))
- kalle \(jag\) ([`applejag`](https://github.com/applejag))
- lestrrat ([`lestrrat`](https://github.com/lestrrat))
- one230six ([`one230six`](https://github.com/one230six))
- purofle
- rustfix ([`rustfix`](https://github.com/rustfix))
- Shaun Mitchell ([`shitchell`](https://github.com/shitchell))
- tploss
- Aristo Chen ([`AristoChen`](https://github.com/AristoChen))
- Bruno Arueira ([`brunoarueira`](https://github.com/brunoarueira))
- Christopher Murphy ([`Splode`](https://github.com/Splode))
- Cristian Dominguez ([`cristiand391`](https://github.com/cristiand391))
- Dawid Dziurla ([`dawidd6`](https://github.com/dawidd6))
- Glauber Santana
- Herby Gillot ([`herbygillot`](https://github.com/herbygillot))
- Jesse Millar ([`jessemillar`](https://github.com/jessemillar))
- Jon Austin ([`jonaustin`](https://github.com/jonaustin))
- João Pedro Veiga  ([`VeigaPunk`](https://github.com/VeigaPunk))
- Justin Moser ([`jmmoser`](https://github.com/jmmoser))
- K\.B\.Dharun Krishna ([`kbdharun`](https://github.com/kbdharun))
- Ang ([`kianmeng`](https://github.com/kianmeng))
- Lars Müller ([`appgurueu`](https://github.com/appgurueu))
- Matt Van Horn ([`mvanhorn`](https://github.com/mvanhorn))
- Nathan Cain ([`nathanscain`](https://github.com/nathanscain))
- NijeboerFrank ([`NijeboerFrank`](https://github.com/NijeboerFrank))
- Nils Vu ([`nilsvu`](https://github.com/nilsvu))

</details>
<!-- veigapunk-upstream-maintainers:end -->

# Glow

Render markdown on the CLI, with _pizzazz_!

<p align="center">
    <img src="https://stuff.charm.sh/glow/glow-banner-github.gif" alt="Glow Logo">
    <a href="https://github.com/charmbracelet/glow/releases"><img src="https://img.shields.io/github/release/charmbracelet/glow.svg" alt="Latest Release"></a>
    <a href="https://pkg.go.dev/github.com/charmbracelet/glow?tab=doc"><img src="https://godoc.org/github.com/golang/gddo?status.svg" alt="GoDoc"></a>
    <a href="https://github.com/charmbracelet/glow/actions"><img src="https://github.com/charmbracelet/glow/workflows/build/badge.svg" alt="Build Status"></a>
    <a href="https://goreportcard.com/report/github.com/charmbracelet/glow"><img src="https://goreportcard.com/badge/charmbracelet/glow" alt="Go ReportCard"></a>
</p>

<p align="center">
    <img src="https://github.com/user-attachments/assets/c2246366-f84b-4847-b431-32a61ca07b74" width="800" alt="Glow UI Demo">
</p>

## What is it?

Glow is a terminal based markdown reader designed from the ground up to bring
out the beauty—and power—of the CLI.

Use it to discover markdown files, read documentation directly on the command
line. Glow will find local markdown files in subdirectories or a local
Git repository.

## Installation

### Package Manager

```bash
# macOS or Linux
brew install glow
```

```bash
# macOS (with MacPorts)
sudo port install glow
```

```bash
# Arch Linux (btw)
pacman -S glow
```

```bash
# Void Linux
xbps-install -S glow
```

```bash
# Nix shell
nix-shell -p glow --command glow
```

```bash
# FreeBSD
pkg install glow
```

```bash
# Solus
eopkg install glow
```

```bash
# Windows (with Chocolatey, Scoop, or Winget)
choco install glow
scoop install glow
winget install charmbracelet.glow
```

```bash
# Android (with termux)
pkg install glow
```

```bash
# Ubuntu (Snapcraft)
sudo snap install glow
```

```bash
# Debian/Ubuntu
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://repo.charm.sh/apt/gpg.key | sudo gpg --dearmor -o /etc/apt/keyrings/charm.gpg
echo "deb [signed-by=/etc/apt/keyrings/charm.gpg] https://repo.charm.sh/apt/ * *" | sudo tee /etc/apt/sources.list.d/charm.list
sudo apt update && sudo apt install glow
```

```bash
# Fedora/RHEL
echo '[charm]
name=Charm
baseurl=https://repo.charm.sh/yum/
enabled=1
gpgcheck=1
gpgkey=https://repo.charm.sh/yum/gpg.key' | sudo tee /etc/yum.repos.d/charm.repo
sudo yum install glow
```

Or download a binary from the [releases][releases] page. MacOS, Linux, Windows,
FreeBSD and OpenBSD binaries are available, as well as Debian, RPM, and Alpine
packages. ARM builds are also available for macOS, Linux, FreeBSD and OpenBSD.

### Go

Or just install it with `go`:

```bash
go install github.com/charmbracelet/glow/v2@latest
```

### Build (requires Go 1.21+)

```bash
git clone https://github.com/charmbracelet/glow.git
cd glow
go build
```

[releases]: https://github.com/charmbracelet/glow/releases

## The TUI

Simply run `glow` without arguments to start the textual user interface and
browse local. Glow will find local markdown files in the
current directory and below or, if you’re in a Git repository, Glow will search
the repo.

Markdown files can be read with Glow's high-performance pager. Most of the
keystrokes you know from `less` are the same, but you can press `?` to list
the hotkeys.

## The CLI

In addition to a TUI, Glow has a CLI for working with Markdown. To format a
document use a markdown source as the primary argument:

```bash
# Read from file
glow README.md

# Read from stdin
echo "[Glow](https://github.com/charmbracelet/glow)" | glow -

# Fetch README from GitHub / GitLab
glow github.com/charmbracelet/glow

# Fetch markdown from HTTP
glow https://host.tld/file.md
```

### Word Wrapping

The `-w` flag lets you set a maximum width at which the output will be wrapped:

```bash
glow -w 60
```

### Paging

CLI output can be displayed in your preferred pager with the `-p` flag. This defaults
to the ANSI-aware `less -r` if `$PAGER` is not explicitly set.

### Styles

You can choose a style with the `-s` flag. When no flag is provided `glow` tries
to detect your terminal's current background color and automatically picks
either the `dark` or the `light` style for you.

```bash
glow -s [dark|light]
```

Alternatively you can also supply a custom JSON stylesheet:

```bash
glow -s mystyle.json
```

For additional usage details see:

```bash
glow --help
```

Check out the [Glamour Style Section](https://github.com/charmbracelet/glamour/blob/master/styles/gallery/README.md)
to find more styles. Or [make your own](https://github.com/charmbracelet/glamour/tree/master/styles)!

## The Config File

If you find yourself supplying the same flags to `glow` all the time, it's
probably a good idea to create a config file. Run `glow config`, which will open
it in your favorite $EDITOR. Alternatively you can manually put a file named
`glow.yml` in the default config path of you platform. If you're not sure where
that is, please refer to `glow --help`.

Here's an example config:

```yaml
# style name or JSON path (default "auto")
style: "light"
# mouse wheel support (TUI-mode only)
mouse: true
# use pager to display markdown
pager: true
# at which column should we word wrap?
width: 80
# show all files, including hidden and ignored.
all: false
# show line numbers (TUI-mode only)
showLineNumbers: false
# preserve newlines in the output
preserveNewLines: false
```

## Contributing

See [contributing][contribute].

[contribute]: https://github.com/charmbracelet/glow/contribute

## Feedback

We’d love to hear your thoughts on this project. Feel free to drop us a note!

- [Twitter](https://twitter.com/charmcli)
- [The Fediverse](https://mastodon.social/@charmcli)
- [Discord](https://charm.sh/chat)

## License

[MIT](https://github.com/charmbracelet/glow/raw/master/LICENSE)

---

Part of [Charm](https://charm.sh).

<a href="https://charm.sh/"><img alt="The Charm logo" src="https://stuff.charm.sh/charm-badge.jpg" width="400"></a>

Charm热爱开源 • Charm loves open source
