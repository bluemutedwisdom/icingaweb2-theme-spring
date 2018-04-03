# Spring theme for Icinga Web 2

#### Table of Contents

1. [About](#about)
2. [License](#license)
3. [Support](#support)
4. [Requirements](#requirements)
5. [Installation](#installation)
6. [Configuration](#configuration)
9. [Contributing](#contributing)

## About

This theme is inspired by spring - warm weather, fuzzy feelings and obviously you don't care much about red dashboards.
Just watch the background image instead ;-)

<img src="https://github.com/dnsmichi/icingaweb2-theme-spring/blob/master/doc/screenshot/login.png" height="300">
<img src="https://github.com/dnsmichi/icingaweb2-theme-spring/blob/master/doc/screenshot/overview.png" height="300">

The background image was taken by myself in Upper Austria, near Linz.

## License

(c) 2018 Michael Friedrich <michael.friedrich@gmail.com>

The theme and images are licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-nc-sa/4.0/).

## Support

Join https://monitoring-portal.org for questions.

## Requirements

* [Icinga Web 2](https://www.icinga.com/products/icinga-web-2/) (>= 2.5.1)

## Installation

Extract this theme to your Icinga Web 2 modules directory as `spring` directory.

Git clone:

```
cd /usr/share/icingaweb2/modules
git clone https://github.com/dnsmichi/icingaweb2-theme-spring.git spring
```

### Enable Icinga Web 2 theme

Enable the module in the Icinga Web 2 frontend in `Configuration -> Modules -> spring -> enable`.
You can also enable the module by using the `icingacli` command:

```
icingacli module enable spring

```

## Configuration

Navigate into `Configuration -> Application` and set the `default theme`.

## Contributing

Edit the CSS and send a PR, including a screenshot how your changes look like :)
