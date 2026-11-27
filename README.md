<p align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.png">
    <img src="assets/header-light.png" width="600" height="160" alt="Excelflow logo and name">
  </picture>
</p>

<p align="center"><b>Spreadsheets and data; a high-performance spreadsheet application built in pure Rust.</b></p>

Excelflow is part of the FlowApps suite. It is a fast, open-source spreadsheet application with a
familiar workflow: the ribbon, formula bar, sheet tabs, tables, charts and pivot tables. It reads and
writes .xlsx natively and runs on macOS and Windows.

## Why Excelflow?

- **Free and open source** — MIT OR Apache-2.0
- **Your files** — .xlsx is the native format: styles, themes, formulas, tables, charts, pivot tables all round-trip; CSV and TSV too
- **500+ functions** — dynamic arrays, LET, LAMBDA, structured table references
- **Pivot tables, charts, conditional formatting** — full spreadsheet workflow
- **Native desktop** — macOS (Apple Silicon) and Windows x64 builds
- **Private** — works offline; no accounts, no telemetry, no cloud

## Features

- **Formulas.** 500+ worksheet functions, dynamic arrays, LET, LAMBDA, MAP, REDUCE, point-mode entry.
- **Tables & charts.** 17 chart types, table styles, sparklines, conditional formatting, colour scales.
- **Pivot tables.** Field list, filters, layouts, date grouping, show-values-as.
- **Formatting.** Accounting formats, cell styles, frozen headers, format painter.
- **File.** Templates, recent workbooks, PDF export and printing.

## Download and install

Download the installer for your system (latest version, 0.1.0 release candidate 1). Excelflow is also available through the [FlowApps launcher](https://github.com/reachneoagent-commits/FlowApps-Launcher/releases/latest).

| Platform | Download |
|---|---|
| macOS, Apple silicon (M1 or newer) | [DMG](https://github.com/reachneoagent-commits/excelflow/releases/download/v0.1.0-rc.3/excelflow-0.1.0-rc.3-macos-arm64.dmg) |
| Windows x64 | [Portable zip](https://github.com/reachneoagent-commits/excelflow/releases/download/v0.1.0-rc.3/excelflow-0.1.0-rc.3-windows-x64-portable.zip) (unzip and run) |

macOS on Intel and a Windows installer are not built yet. Older versions and checksums are on the [Releases page](https://github.com/reachneoagent-commits/excelflow/releases).

The app is not code-signed with a paid certificate, so macOS and Windows warn you the first time you open it. Every release lists SHA-256 checksums to check the files against.

- **Mac:** open the DMG and drag Excelflow to Applications. Then right-click Excelflow, choose Open, and click Open again.
- **Windows:** if SmartScreen appears, click More info, then Run anyway.

## Supported platforms

- **Desktop app:** macOS on Apple Silicon; Windows x64 (Intel Mac build planned)

## Build from source

You need [Rust](https://rustup.rs/) 1.95+. Then run:

```bash
cargo build --release -p gridcraft
```

The desktop app binary is produced under `target/release/`.

## About this fork

Excelflow is based on [GridCraft](https://github.com/storytold/gridcraft) by the ArtCraft team, rebranded as a FlowApps product. The original project is dual-licensed under MIT or Apache-2.0; that licensing is preserved here.

The ArtCraft name, wordmark and logos remain trademarks of the ArtCraft Team and are not used in Excelflow. Per the original NOTICE, forks and modified versions must remove them.

## Credits & Acknowledgments

Full third-party credits are in [`NOTICE`](NOTICE) and [`ATTRIBUTION.md`](ATTRIBUTION.md).

- **[GridCraft](https://github.com/storytold/gridcraft)** by the ArtCraft team: the original spreadsheet engine, UI and file formats (MIT OR Apache-2.0).
- **[craft-libs](https://github.com/storytold/craft-libs)** by the ArtCraft team: the shared UI framework and file-format libraries this app is built on, plus [egui](https://github.com/emilk/egui) (MIT OR Apache-2.0).
- **FlowApps branding, logo and symbol:** Reach Neo (trademark of Reach Neo).

Excelflow is not affiliated with or endorsed by ArtCraft or the GridCraft contributors.

## License

Excelflow is dual-licensed under [MIT](LICENSE-MIT) or [Apache-2.0](LICENSE-APACHE), at your option.

**Copyright (c) 2026 Reach Neo and the Excelflow contributors.**
