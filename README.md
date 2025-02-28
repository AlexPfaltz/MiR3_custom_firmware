# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

A template for building OpenWrt with GitHub Actions

## Usage

- Select `Build OpenWrt` on the Actions page.
- Click the `Run workflow` button.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

## Tips

- WiFi is turned off by default
- The firmware is compiled from the official OpenWRT source, with the addition of third-party drivers to the assembly to support mir3. The drivers were taken from the X-WRT source code.
- In addition to the packages installed by default, the assembly includes: ca-certificates, luci-i18n-base-ru.
- During the build process, the md5 amount from the official version is assigned to the kernel so that kmod packages can be installed from the official repository. Firmware compatibility with all packages is not guaranteed. Installing kmod modules may disrupt the system.

## Credits

- [OpenWrt](https://github.com/openwrt/openwrt)
- [X-Wrt](https://github.com/x-wrt/x-wrt)

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)
