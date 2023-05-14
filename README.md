# qr2clip

Read a QR code within a screen-grab and put it in your clipboard.

`qr2clip` uses `zbarimg` to perform QR code recognition and tries to remain package agnostic for additional tasks (see: Dependencies).

## Installation
```bash
# Install to /usr/local/bin
cd /usr/local/bin
sudo wget https://raw.githubusercontent.com/ulfnic/ocr2clip/main/qr2clip
sudo chmod +x ./qr2clip

# Test run
qr2clip

# Satisfy dependencies if prompted to do so.
```

## Dependencies
- `qr2clip`

#### X11:
- `maim` or `import`
- `xclip` or `xsel`

#### Wayland:
- `grim`
- `slurp`
- `wl-copy`

## Troubleshooting

#### "command not found":

- Make sure `/usr/local/bin` is in your $PATH or run it explicitly using `/usr/local/bin/ocr2clip`

## License
Licensed under GNU Affero General Public License v3. See LICENSE for details.
