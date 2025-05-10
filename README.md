# 📌 Linguino

[![License](https://img.shields.io/github/license/kdsn/plugin-template)](LICENSE)
[![Contributors](https://img.shields.io/github/contributors/kdsn/plugin-template)](https://github.com/kdsn/plugin-template/graphs/contributors)

🔹 **Short description:**  
Linguino is a minimal multilingual plugin for WordPress, using native APIs and subdirectory-based language switching.

## **Demo / Live Version**
[🔗 (coming soon)](https://kdsn.dk) 

## **Screenshots**
![Screenshot](docs/screenshot1.png)  

## Features
  ✅ Language configuration with defaults <br>
  ✅ Subdirectory-based URL rewriting <br>
  ✅ Automatic detection and formatting of date/time per language <br>
  ✅ Translation group support between posts/pages <br>
  ✅ Frontend language switcher (shortcode/widget) <br>
  ✅ Simple admin interface for managing languages and translations <br>

## Tech Stack & Dependencies
| Technology | Version  |
|-----------|-----------|
| PHP       | 7.4 / 8.x |
| WordPress | 6.x+      |

## Installation

### Option 1: Upload via WordPress Admin
```txt
1. Go to Plugins > Add New

2. Click "Upload Plugin"

3. Select linguino.zip

4. Click "Install Now"

5. Activate the plugin

```

### Option 2: Manual Installation
```txt
1. Clone the repository:
   git clone https://github.com/kdsn/linguino.git

2. Copy the folder into:
   wp-content/plugins/

3. Activate it via the WordPress admin panel.

```

## Usage
Once activated:
- Configure languages via Settings > Linguino
- Add [linguino_switcher] to your theme or content
- Manage translations via the post editor and “Add translation” UI

## Architecture & Design
Plugin structure follows standard WP practices.
All logic is encapsulated in plugin root, with admin and public logic separated.

## Roadmap & Future Updates
- ACF & WooCommerce integration
- JSON-based language definitions
- Language fallback chain

## Contributing
We welcome contributions! See [`docs/contributing.md`](docs/contributing.md) for guidelines.

## Issues & Bug Reports
Found a bug? [Open an issue](https://github.com/kdsn/linguino/issues).

## License
This plugin is licensed under the MIT License.
See the [`LICENSE`](LICENSE)   file for more details.

## Acknowledgments
Credits to WordPress Plugin Boilerplate and any other frameworks, libraries, or tools used.
