<p align="center">
    <img src="telegram.png" alt="Telegram logo" width=128 height=128>

<h2 align="center">Telegram AppImage</h2>

  <p align="center">
    Telegram Stable AppImages by GitHub Actions Continuous Integration
    <br>
    <a href="https://github.com/srevinsaju/Telegram-Appimage/issues/new">Report bug</a>
    ·
    <a href="https://github.com/srevinsaju/Telegram-Appimage/issues/new">Request feature</a>
  </p>
</p>

## Get Started

Download the latest release from

| Stable | 
| ------- |
| [Download](https://github.com/srevinsaju/Telegram-AppImage/releases/tag/continuous) |

### Executing
#### File Manager
Just double click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some rare cases
the `+x` permissisions. So, right click > Properties > Allow Execution

#### Terminal 
```bash
./Telegram-*.AppImage
```
```bash
chmod +x Telegram-*.AppImage
./Telegram-*.AppImage
```

In case, if FUSE support libraries are not installed on the host system, it is 
still possible to run the AppImage

```bash
./Telegram-*.AppImage --appimage-extract
cd squashfs-root
./AppRun
```

## Note
> This is not an official AppImage. The developer of this continuous integration
> take no responsibility over anything which happen using this AppImage. USE IT ONLY
> ON YOUR OWN RISK. You are "free" to fork this repository, analyze the code and
> build your own AppImage under the MIT License and GNU GPL v3 License

## License
"Telegram Desktop" is licensed under the [GNU GPL v3](https://github.com/telegramdesktop/tdesktop/blob/dev/LICENSE)
The official source code of the Telegram is available at links provided 
* https://github.com/telegramdesktop/tdesktop

"GitHub Continuous Integration" is licensed under the MIT License. 
