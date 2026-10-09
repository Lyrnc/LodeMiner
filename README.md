<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/lodeminer-banner-dark.png">
    <img src="assets/lodeminer-banner.png" alt="LodeMiner" width="520">
  </picture>
</p>

<p align="center">
  Cryptocurrency miner for NVIDIA GPUs.
</p>

## Download

The first public release is coming soon. Click **Watch** at the top of this page, then **Custom** > **Releases**,
to get a notification when it's out.

## Algorithms

| Algorithm | Coin | Fee |
|---|---|---|
| quantus | Quantus (QTC) | 1.0% |

More algorithms are on the way.

## Supported GPUs

NVIDIA only:

- Blackwell (RTX 50 series)
- Ada Lovelace (RTX 40 series)
- Ampere (RTX 30 series)
- Turing (RTX 20 series, GTX 16 series)

Driver 576.02 or newer.

## Supported systems

- Windows 10 / 11 (64-bit)
- Linux and HiveOS: coming soon

## Features

- Failover pools
- Temperature limit with automatic pause and resume
- Power limit and fan control
- HTTP API for monitoring
- JSON config file
- Per-GPU selection
- Hotkeys: `h` stats, `p` pause, `r` resume, `q` quit
- Kryptex account login with your email, no wallet needed

## Quick start

```bat
lodeminer.exe -a quantus -o qtc-eu.kryptex.network:7049 -u YOUR_WALLET -w rig1
```

Run `lodeminer.exe --help` for all options. The release zip includes a ready-to-edit `start.bat`.

## Support

- Bugs: [open a bug report](https://github.com/Lyrnc/LodeMiner/issues/new?template=bug_report.yml)
- Hashrate on your card: [send a hashrate report](https://github.com/Lyrnc/LodeMiner/issues/new?template=hashrate_report.yml)
- Security issues: see [SECURITY.md](SECURITY.md)

## License

Free to use, not open source. See [LICENSE](LICENSE). Built on
[quantus-miner](https://github.com/Quantus-Network/quantus-miner) (Apache 2.0, see [NOTICE](NOTICE)) and other
open-source libraries; their licenses ship in the download.
