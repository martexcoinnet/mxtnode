<h1 align="center"> MARTEXCOIN Node</h1>


## 🚀️ Getting started

A quick introduction of the minimal setup you need to get a running node. 

*Prerequisites:*
- JAVA `openjdk-11-jre`
-   `mxt-all*.jar` and `mxt.conf` files from [releases](https://github.com/martexcoinnet/mxtnode/releases) 

Linux systems:
```bash
sudo apt-get update
sudo apt-get install openjdk-11-jre
java -jar node/target/mxt-all*.jar path/to/config/mxt.conf
```

Mac systems (assuming already installed homebrew):
```bash
brew cask install adoptopenjdk/openjdk/adoptopenjdk11
java -jar node/target/mxt-all*.jar path/to/config/mxt.conf
```

Windows systems (assuming already installed OpenJDK 11):
```bash
java -jar node/target/mxt-all*.jar path/to/config/mxt.conf
```
