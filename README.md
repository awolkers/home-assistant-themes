[![Build Status](https://www.travis-ci.org/awolkers/home-assistant-themes.svg?branch=master)](https://www.travis-ci.org/awolkers/home-assistant-themes)
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)

# Dark theme pack for Home Assistant
A collection of dark themes for [Home Assistant](https://www.home-assistant.io/). Read the [frontend](https://www.home-assistant.io/components/frontend/) documentation for more information on how to include themes within Home Assistant or read the instructions below. The dark theme comes in five colors:

* [Themes](#themes)
    * [Dark Blue](#dark-blue)
    * [Dark Green](#dark-green)
    * [Dark Turqoise](#dark-turqoise)
    * [Dark Orange](#dark-orange)
    * [Dark Yellow](#dark-yellow)
* [Installation](#installation)
    * [HACS](#hacs)
    * [Manual](#manual)

## Themes

### Dark Blue
![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/examples/dark_blue.png)

### Dark Green
![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/examples/dark_green.png)

### Dark Turqoise
![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/examples/dark_turqoise.png)

### Dark Orange
![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/examples/dark_orange.png)

### Dark Yellow
![alt text](https://raw.githubusercontent.com/awolkers/home-assistant-themes/master/examples/dark_yellow.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS (comming soon...)

1. Go to the Community Store.
2. Search for `Template`.
3. Navigate to `Template` theme.
4. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.

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
