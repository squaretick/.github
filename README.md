<h1 align="center">Squaretick</h1>

<p align="center">
  <em>Sharp tools for people who ship.</em>
</p>

<p align="center">
  Single-binary developer infrastructure — no runtimes, no daemons, no yak-shaving.
</p>

---

## Projects

### 🛰️ [Pulsate](https://github.com/squaretick/pulsate)

**A reverse-proxy gateway in one binary.**

Routing, TLS, and traffic control without a stack of sidecars. Drop in one
binary (`pulsate`, or the `p8` alias) and go.

```sh
curl --proto '=https' --tlsv1.2 -fsSL \
  https://raw.githubusercontent.com/squaretick/pulsate/main/scripts/install.sh | sh
```

---

### 🧰 [Vanta](https://github.com/squaretick/vanta)

**Every developer tool, one command.**

Install, pin, and switch developer tooling from a single binary (`vanta`, or
the `vt` alias). One command instead of ten package managers.

```sh
curl --proto '=https' --tlsv1.2 -fsSL \
  https://raw.githubusercontent.com/squaretick/vanta/main/scripts/install.sh | sh
```

---

## Install Anywhere

Prebuilt binaries are available for:

- **Linux** (x86_64 / aarch64, GNU + musl)
- **macOS** (Intel + Apple Silicon)
- **Windows** (x86_64)

Every release includes SHA256 checksums.

Prefer a package manager or container?

```sh
cargo install pulsate
cargo install vanta
```

```text
ghcr.io/squaretick/pulsate
ghcr.io/squaretick/vanta
```

---

<p align="center">
  <sub>
    <a href="https://github.com/squaretick">github.com/squaretick</a>
  </sub>
</p>
