<!-- Source: Best-README-Template BLANK_README (Unlicense) — https://github.com/othneildrew/Best-README-Template -->
<a id="readme-top"></a>

# MyWorld_of_Tanks-Videos

An archived personal collection of 63 World of Tanks match replay files (.wotreplay) recorded in July and August 2019, with no source code, manifest, or build to run.

**English** · [简体中文](README.zh-CN.md)

[![License](https://img.shields.io/github/license/anyingiit/MyWorld_of_Tanks-Videos)](LICENSE)

[Report a bug](https://github.com/anyingiit/MyWorld_of_Tanks-Videos/issues/new?template=bug_report.yml) · [Request a feature](https://github.com/anyingiit/MyWorld_of_Tanks-Videos/issues/new?template=feature_request.yml)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

MyWorld_of_Tanks-Videos is anyingiit's personal archive of match recordings from Wargaming's *World of Tanks*, saved in the game client's native `.wotreplay` format rather than as video. The repository holds 63 replay files: 61 at the root, recorded between 24 July and 9 August 2019, plus two of the later matches duplicated into a subfolder whose name is Chinese for "highlight replays". Each filename encodes the capture timestamp, the nation and vehicle used in that battle (for example `japan-J25_Type_4`, `sweden-S17_EMIL_1952_E2`, `china-Ch01_Type59` and `usa-A17_M37`) and the battle map, but the repository carries no source code, package manifest, or build of any kind — GitHub lists it as archived, and opening a replay requires the World of Tanks client itself.

See the [open issues](https://github.com/anyingiit/MyWorld_of_Tanks-Videos/issues) for anything planned.

## Getting Started

### Prerequisites

- The [World of Tanks](https://worldoftanks.eu) game client (or a compatible third-party replay viewer), since a `.wotreplay` file is only played back through the client's own replay engine
- Nothing else: the repository has no package manifest and no build configuration of any kind

### Installation

There is no build step and nothing to compile. Cloning the repository gets you a local copy of the replay files:

```sh
git clone https://github.com/anyingiit/MyWorld_of_Tanks-Videos.git
cd MyWorld_of_Tanks-Videos
```

## Usage

Every file in the repository is a `.wotreplay` recording; play one back through the World of Tanks client, for example:

```sh
20190724_1955_japan-J25_Type_4_05_prohorovka.wotreplay
```

World of Tanks associates the `.wotreplay` extension with itself on install, so double-clicking a file (or copying it into the client's own `replays/` folder before launching the game) opens it in the client's replay viewer. There is no other viewer, converter, or export step in this repository, and a replay this old may not play back exactly if the game's data has changed significantly since 2019.

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) for how to open an issue or a pull request, and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for the standards expected of everyone taking part.

Please do not report security issues in public issues or pull requests. [SECURITY.md](SECURITY.md) explains how to report them privately.

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact

Project link: [https://github.com/anyingiit/MyWorld_of_Tanks-Videos](https://github.com/anyingiit/MyWorld_of_Tanks-Videos)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
