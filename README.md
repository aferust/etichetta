# Etichetta [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/trikko/etichetta/blob/main/LICENSE) [![Donate](https://img.shields.io/badge/paypal-buy_me_a_beer-FFEF00?logo=paypal&logoColor=white)](https://paypal.me/andreafontana/5)
<sub>International Phonetic Alphabet: /e-ti-'ket-ta/ [mp3](https://www.dropbox.com/scl/fi/ow41ztln8vcbw8t10bcd1/etichetta.mp3?rlkey=6lecfwxq9h2aj6nzzimjlejdp&st=n1d6clii&dl=0)</sub>

Etichetta is a project that aims to provide a simple and efficient way to annotate images.

## Prebuilt packages (Linux, Windows)
> [!NOTE]
> The packages are not yet available. You can build and run a preview version of etichetta by following the instructions below.

[![Snap](https://img.shields.io/badge/-Linux_SNAP_-red.svg?style=for-the-badge&logo=linux)](https://github.com/trikko/tshare/releases/latest/download/etichetta.snap)

[![Windows](https://img.shields.io/badge/-Windows_installer-blue.svg?style=for-the-badge&logo=windows)](https://github.com/trikko/tshare/releases/latest/download/etichetta-setup.exe)

## Build from source (Linux, Windows)

To build etichetta from source install a dlang compiler (DMD, LDC, GDC), checkout this repository and build.

```bash
git clone https://github.com/trikko/etichetta
dub --build=release
```

## Etichetta on macOS (with Docker and XQuartz)

To run etichetta on a macOS machine, you can run it inside a Docker container and connect a display, using XQuartz.

You can use the scripts inside the folder `deployment`.

Build the last docker image running `./build-docker-etichetta.sh` and run it using `./run-docker-etichetta.sh`

## License

This project is licensed under the [MIT License](https://github.com/your-username/etichetta/blob/main/LICENSE).