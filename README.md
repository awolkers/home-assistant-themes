# Dark theme pack for Home Assistant

[![Build Status](https://travis-ci.com/awolkers/home-assistant-themes.svg?branch=master)](https://travis-ci.com/awolkers/home-assistant-themes)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg)](https://github.com/hacs/integration)

A collection of dark themes for [Home Assistant](https://www.home-assistant.io/). Read the
[frontend](https://www.home-assistant.io/components/frontend/) documentation for more information on how to include
themes within Home Assistant or read the instructions below.

- [Themes](#themes)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [HACS](#hacs)
  - [Manual](#manual)

## Themes

This theme pack comes in the following colors.

- [Dark Blue](#dark-blue)
- [Dark Green](#dark-green)
- [Dark Orange](#dark-orange)
- [Dark Pink](#dark-pink)
- [Dark Turqoise](#dark-turqoise)
- [Dark Yellow](#dark-yellow)

### Dark Blue

![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/docs/dark_blue.png)

### Dark Green

![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/docs/dark_green.png)

### Dark Orange

![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/docs/dark_orange.png)

### Dark Pink

![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/docs/dark_pink.png)

### Dark Turqoise

![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/docs/dark_turqoise.png)

### Dark Yellow

![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/docs/dark_yellow.png)

## Installation

### Prerequisites

Add the following code to your `configuration.yaml` file and restart Home Assistant.

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

### HACS

1. Go to the Community Store.
2. Click the + icon to add a repository.
3. Search for `Dark theme pack for Home Assistant`.
4. Click and press `Download`.
5. Go to the "Services" tab under Developer Tools and trigger the `frontend.reload_themes` service.

### Manual

1. Create a new folder named `themes` within the `/config` folder.
2. Copy the `/themes/dark_themes.yaml` from this repo to the created `config/themes/` folder.
3. Go to the "Services" tab under Developer Tools and trigger the `frontend.reload_themes` service.
