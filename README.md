[![Build Status](https://travis-ci.com/awolkers/home-assistant-themes.svg?branch=master)](https://travis-ci.com/awolkers/home-assistant-themes)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg)](https://github.com/hacs/integration)

# Dark theme pack for Home Assistant

A collection of dark themes for [Home Assistant](https://www.home-assistant.io/). Read the [frontend](https://www.home-assistant.io/components/frontend/) documentation for more information on how to include themes within Home Assistant or read the instructions below.

- [Themes](#themes)
  - [Dark Blue](#dark-blue)
  - [Dark Green](#dark-green)
  - [Dark Turqoise](#dark-turqoise)
  - [Dark Orange](#dark-orange)
  - [Dark Yellow](#dark-yellow)
- [Installation](#installation)
  - [HACS](#hacs)
  - [Manual](#manual)

## Themes

The dark theme comes in these five colors.

### Dark Blue

![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/docs/dark_blue.png)

### Dark Green

![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/docs/dark_green.png)

### Dark Turqoise

![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/docs/dark_turqoise.png)

### Dark Orange

![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/docs/dark_orange.png)

### Dark Yellow

![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/docs/dark_yellow.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Click the + icon to add a repository.
3. Search for `Dark theme pack for Home Assistant`.
4. Click and press `Install`.
5. Go to services and trigger the `frontend.reload_themes` service.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/home-assistant-community-themes/template.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/home-assistant-community-themes/template.git
```
