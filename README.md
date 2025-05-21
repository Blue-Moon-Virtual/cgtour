# CGI Virtual Tour Render Helper

[![Blender](https://img.shields.io/badge/Blender-3.0%2B-orange?logo=blender)](https://www.blender.org/)
[![Version](https://img.shields.io/badge/version-0.0.9-blue)](https://github.com/BlueMoonVirtual/cgtour)

A Blender addon to dynamically adjust render resolution and settings for CGI virtual tours, making it easy to render panoramic and standard frames in a single animation.

## Features
- Automatically switches between panoramic (8000x4000) and standard (1920x1120) resolutions based on frame number.
- Custom output directory and filename pattern.
- Simple UI in the Render Properties panel.
- Robust error handling for GPU memory and render errors.

## Installation
1. Download or clone this repository.
2. In Blender, go to **Edit > Preferences > Add-ons > Install**.
3. Select the `cgtour` folder (or zip it first) and install.
4. Enable the addon in the Add-ons list.

## Usage
- In the **Render Properties** panel, find the **CGI Virtual Tour** section.
- Enable the addon, set the number of panoramic images, output directory, and filename pattern.
- Use the provided operator to render your animation with dynamic settings.

## Author
- **Artemiy Vrubel**

## Maintainer
- **Blue Moon Virtual**

## License
MIT License

---

For issues, suggestions, or contributions, please open an issue or pull request on GitHub. 