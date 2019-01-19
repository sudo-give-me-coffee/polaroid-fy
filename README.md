# polaroid-fy
Turn your pictures into cute polaroids. This tool creates a border and distort the image leaving the image similar to polaroids , see the example:

![Image: original](https://github.com/sudo-give-me-coffee/polaroid-fy/raw/master/example/example.jpg)

After

![Image: after filter](https://github.com/sudo-give-me-coffee/polaroid-fy/raw/master/example/example-polaroid-out.jpg)

<hr>

## Usage:

```bash
polaroid-fy filename [text]
```

`[text]` is a optional argument it will be added at bottom of polaroid

### Dependencies:
* imagemagick
> An AppImage will be provided to dispense dependencies


### TODO:
- [x] The script
- [x] This ReadME
- [ ] A GUI tool
- [ ] A DEB Package
- [ ] AppImage with dependencies

### Install:

1) Download it:
```bash
wget -c https://raw.githubusercontent.com/sudo-give-me-coffee/polaroid-fy/master/polaroid-fy
```
2) Turn executable:
```bash
chmod +x polaroid-fy
```
3) Move to /usr/bin:
```bash
sudo mv polaroid-fy /usr/bin
```

### Uninstall:

1) Run it:
```bash
sudo rm /usr/bin/polaroid-fy
```
<hr>

### FAQ
- **Will you provide a flatpak?**

No, Flatpak is a worst way to distribute application, but if you want you can make it

- **Will you add more filters?**

In this tool no, but open an issue with describing filter that i will try create a tool that apply it


