# Clash of Clans Loot Collector
[How to pronounce _**cocloolector**_?](https://translate.google.com/translate_tts?ie=UTF-8&q=cocloolector&tl=ja&total=1&idx=0&textlen=12&tk=850673|713841&client=t&prev=input)

### What it does?
This program will launch the game based on auto discover connected Android devices or emulators/simulators (such as Genymotion) that have **com.supercell.clashofclans** installed, and start collecting loot into storage periodically with random interval.

_Notes: Tested running one instance of cocloolector that discovered and collecting loots from 2 connected Android phone and 4 genymotion simulator simulteneously on Mac with Intel Core i7 2Ghz, 8GB ram._

### Basic Installation
You can install cocloolector via the command-line with either `curl` or `wget`.

#### via curl
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/alwinchan/cocloolector/master/install.sh)"`

#### via wget
`sh -c "$(wget https://raw.githubusercontent.com/alwinchan/cocloolector/master/install.sh -O -)"`

### How to start?
```
cd cocloolector
python autoDiscover.py
```

### Limitations
It has only been tested on device and simulator with 720x1280 as resolution.

### Roadmap
* Aut Troops Request and Donate
* Replay Uploader
* Auto Upgrade Building, Troops, Spells

## License
cocloolector is released under the [Apache License 2.0](https://github.com/alwinchan/cocloolector/blob/master/LICENSE).