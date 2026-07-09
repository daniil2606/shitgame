welcome to this repository for the shit game</br>
all thanks to lune</br>
their repo: https://github.com/lune-org/lune/</br>
their docs: https://lune-org.github.io/docs/</br>
how to run the linux-aarch64 version on termux:</br>
```bash
pkg update && pkg install proot proot-distro && proot-distro install ubuntu && proot-distro login ubuntu -- bash -c "curl -L -O "https://github.com/daniil2606/shitgame/releases/download/rupatch/shitgame-linux-aarch64" && chmod +x ./shitgame-linux-aarch64 && ./shitgame-linux-aarch64"
```
if still in ubuntu mode, run this:</br>
```bash
./shitgame-linux-aarch64
```
if termux was closed, use this:</br>
```bash
proot-distro login ubuntu -- bash -c "./shitgame-linux-aarch64"
```
im giving you all this in case you are a linux idiot
