# MusicPlayer
[![Build Status](https://travis-ci.org/HuberTRoy/MusicBox.svg?branch=master)](https://travis-ci.org/HuberTRoy/MusicBox)  
[![Python](https://img.shields.io/badge/Python-3.5%203.6-green.svg)](https://pypi.python.org/pypi/Music-Player)  
[![Enjoy](https://img.shields.io/badge/EnjoyYourself-yes-orange.svg)](https://github.com/Dubby0610/MusicBox/)  
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://pypi.python.org/pypi/Music-Player)  

## Overview
A cross-platform music player that integrates multiple music services (currently **NetEase Cloud Music, Xiami, and QQ Music**) ✧( •̀ω•́ )✧  

## Features
- Playlists, search, playback, and lyrics support for **NetEase, Xiami, and QQ Music**.  
- Smart song recommendations based on what you listen to.  
- Desktop lyric system.  
- Music download support.  
- NetEase account login via phone number to sync playlists.  
- User experience close to the official NetEase Cloud Music client.  
- Cross-platform support.  
- Easy UI customization with QSS (similar to CSS).  

## Screenshots
<img src="https://github.com/Dubby0610/MusicBox/blob/master/testpic/24.jpg"/>  
<img src="https://github.com/Dubby0610/MusicBox/blob/master/testpic/16.jpg"/>  
<img src="https://github.com/Dubby0610/MusicBox/blob/master/testpic/19.jpg"/>  
<img src="https://github.com/Dubby0610/MusicBox/blob/master/testpic/23.jpg"/>  

## Installation
From PyPI:
```bash
(sudo) pip install Music-Player
✨🍰✨
```
Or from source:
```bash
git clone git@github.com:Dubby0610/MusicBox.git
(sudo) python3 setup.py install
```

## Usage
```bash
(sudo) musicplayer
```

## Troubleshooting
If you encounter dependency errors:  
- On **Windows**, if `pycryptodome` fails, use:  
  ```bash
  pip install pycryptodomex
  ```  

### Extra dependencies on Linux/*nix:
```bash
sudo apt-get install pyqt5.qtmultimedia
sudo apt-get install libqt5multimedia5-plugins
```

### QQ Music playback dependencies:
- On **Windows**: If m4a decoder is missing, install [LAV Filters](https://github.com/Nevcairiel/LAVFilters/releases).  
- On **Linux**: Install [GStreamer](https://gstreamer.freedesktop.org/).  

## Development
See [update log](https://github.com/HuberTRoy/MusicPlayer/blob/master/doc/updateLog.md) for detailed development history.  

### Feature TODOs
- [ ] Support private FM.  
- [ ] Create custom playlists.  
- [ ] Package releases for easier installation.  
- [ ] Multi-platform account sync.  
- [ ] Theme/skin customization.  
- [x] Song downloading.  
- [x] Basic recommendations.  
- [x] Desktop lyric system.  

### Development TODOs
- [x] Add logging for easier debugging.  
- [ ] Experiment with alternative playback methods.  
