# sddm-spacecraft-theme

A theme for the [SDDM login manager](https://github.com/sddm/sddm).

- Screen resolution: 1080p
- Font: JetBrainsMono Nerd Font

### Dependencies

```sh
qt6-5compat qt6-declarative qt6-svg sddm
```
> qt6-declarative replaces qt6-quickcontrols2
> https://archlinux.org/packages/extra/x86_64/qt6-declarative/

### Install

1. Clone this repository:

   ```sh
   sudo git clone https://github.com/HttpRafa/sddm-spacecraft-theme.git /usr/share/sddm/themes/sddm-spacecraft-theme
   ```

2. Then edit `/etc/sddm.conf`, so that it looks like this:

    ```sh
    echo "[Theme]
    Current=sddm-spacecraft-theme" | sudo tee /etc/sddm.conf
    ```

### Credits

Based on the theme [`sddm-astronaut-theme`](https://github.com/Keyitdev/sddm-astronaut-theme) by **Keyitdev**.

### License

Distributed under the **[GPLv3+](https://www.gnu.org/licenses/gpl-3.0.html) License**.    
Copyright (C) 2022-2024 HttpRafa.
