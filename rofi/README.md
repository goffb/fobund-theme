# fobund-rofi

fobund theme for [rofi](https://github.com/davatorium/rofi).

## install

clone the repository, then copy one of the three themes to your rofi configuration:

note: if you already have an existing rofi configuration, you might want to back it up first:
```bash
mv ~/.config/rofi/config.rasi ~/.config/rofi/config.bak
```

```bash
git clone https://github.com/goffb/fobund-theme.git
mkdir -p ~/.config/rofi
cp fobund-theme/rofi/fobund1.rasi ~/.config/rofi/config.rasi
```

to use another variant, replace fobund1.rasi with fobund2.rasi or fobund3.rasi.

> note: for the best match with the screenshots, use the font and icon theme below.

```rasi
configuration {
    font: "SF Pro Display Medium 12";
    icon-theme: "Papirus-Dark";
}
