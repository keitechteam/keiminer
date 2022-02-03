```
 /$$   /$$           /$$ /$$      /$$ /$$                              
| $$  /$$/          |__/| $$$    /$$$|__/                              
| $$ /$$/   /$$$$$$  /$$| $$$$  /$$$$ /$$ /$$$$$$$   /$$$$$$   /$$$$$$ 
| $$$$$/   /$$__  $$| $$| $$ $$/$$ $$| $$| $$__  $$ /$$__  $$ /$$__  $$
| $$  $$  | $$$$$$$$| $$| $$  $$$| $$| $$| $$  \ $$| $$$$$$$$| $$  \__/
| $$\  $$ | $$_____/| $$| $$\  $ | $$| $$| $$  | $$| $$_____/| $$      
| $$ \  $$|  $$$$$$$| $$| $$ \/  | $$| $$| $$  | $$|  $$$$$$$| $$      
|__/  \__/ \_______/|__/|__/     |__/|__/|__/  |__/ \_______/|__/      
```

## Download

[KeiMiner v1.1](https://github.com/keitechteam/keiminer/releases/tag/1.1)

## Support

* Telegram: [@keiminer](https://t.me/keiminer)

## Description

* Based on [TON team official solo miner](https://github.com/tontechio/pow-miner-gpu). 
* Suitable for mining on [Ton Whales pool](https://tonwhales.com/docs/pool) only.
* CPU and GPU mining support.
* Both CLI and GUI versions available.
* Platform: Windows only (Linux version coming soon).
* Fee: 1% (one share of every 100 shares goes to dev).

## CLI options

* `-w`, `--wallet` - specify your wallet
* `-d`, `--devices` - specify mining device IDs (space-separated)
* `-h` - show help message

Example run:
```
keiminer.exe -w EQAAFhjXzKuQ5N0c96nsdZQWATcJm909LYSaCAvWFxVJP80D -d 0 1
```

## Troubleshooting

* _Problem_: **Windows "VCRUNTIME140_1.dll not found" error**.
* _Solution_: Download and install the latest [Visual C++ Redistributable](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) package for your Windows version (32 or 64 bit).
