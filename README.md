# Pyneko  

A cross-platform manga downloader for **Linux, Windows, and MacOS**, based on [HakuNeko](https://github.com/manga-download/hakuneko). It incorporates code from **SmartStitch** for advanced image slicing and utilizes **waifu2x** for image upscaling, ensuring fast and seamless downloads.

<a href="https://github.com/Lyem/pyneko/releases">
    <img src="https://img.shields.io/github/downloads/Lyem/pyneko/total" />
</a>&nbsp;&nbsp;
<a href="https://discord.gg/EYm6svnw5b">
<img alt="Discord" src="https://img.shields.io/discord/1263906403953672344?label=Discord&labelColor=5864f2&color=545454&cacheSeconds=36000"/>
</a>

## Installation & Usage  
```bash
poetry install    # Install dependencies  
poetry run start  # Start the application  
poetry run build  # Build the project  
poetry run clean  # Clean __pycache__  
poetry run new    # Create a new provider  
```

## Dependencies  

🌎 **Global**: Chrome  

🐧 **Linux/BSD**:  
  - **KDE**: Native support (requires `dbus`, `klipper`, and `dbus-python`, usually pre-installed).  
  - **X11**: Install `xsel` or `xclip`  
    ```bash
    sudo zypper install xsel  # or  
    sudo zypper install xclip  
    ```  
  - **Wayland**: Install `wl-clipboard`  
    ```bash
    sudo zypper install wl-clipboard  
    ```


## Credits

This project uses code from the [SmartStitch](https://github.com/MechTechnology/SmartStitch) for image slicing.

## Sponsors ❤️

Check out our awesome sponsors!

<a href="https://github.com/Benjigx"><img src="https://github.com/Benjigx.png" width="80px" alt="Benjigx" /></a>&nbsp;&nbsp;