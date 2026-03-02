# immich-kiosk-plymouth-theme

Simple Plymouth theme for Immich Kiosk


The theme is a blank screen with a spinning logo (below) in the center.

<div style="background-color: #000000; color: #ffffff; padding: 20px;">
    <img src="./assets/spinner.gif" alt="Logo">
</div>


## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/damongolding/immich-kiosk-plymouth-theme.git
    ```
2. Install the theme:
    ```bash
    cd immich-kiosk-plymouth-theme
    sudo cp -r immich-kiosk /usr/share/plymouth/themes
    ```
3. Enable the theme:
    ```bash
    sudo plymouth-set-default-theme -R immich-kiosk
    ```
