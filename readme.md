# Child Theme

> A WordPress child theme for developing custom websites. This child theme is used to speed up development and is compatible with [Astra](https://wpastra.com/) and [Beaver Builder Theme](https://www.wpbeaverbuilder.com/wordpress-framework-theme/).

[🚀 Download the latest version here.](https://update.sitepilot.io/v3/download/child-theme)

## Usage

1. Clone this repository (replace `theme-name` with the desired theme name): `git clone https://github.com/sitepilot/child-theme.git theme-name && rm -rf theme-name/.git`.
2. Modify `style.css` to your needs. 
   * Optional: replace `bb-theme` with `astra` if you would like to use Astra.
3. Install composer packages: `composer install`.
4. Install node modules: `npm install`.
5. Start compiling scripts and stylesheets: `npm start`.

*This child theme includes the [WPGulp](https://github.com/ahmadawais/WPGulp) workflow for compiling SCSS and Javascript, you can find more information about WPGulp [here](https://github.com/ahmadawais/WPGulp).*