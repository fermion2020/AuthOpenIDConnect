# AuthOpenIDConnect - LimeSurvey Auth Plugin

[![Build plugin](https://github.com/fermion2020/AuthOpenIDConnect/actions/workflows/build.yml/badge.svg)](https://github.com/fermion2020/AuthOpenIDConnect/actions/workflows/build.yml)

## Disclaimer
Original plugin by https://github.com/Shnoulle/AuthOpenIDConnect

updated by fermion2020

## Updates
Updated the compatibility in the config.xml file

## Install

Use the [releases](https://github.com/fermion2020/AuthOpenIDConnect/releases) page to download the latest built version. Or go through the build process on your environment.

1. Clone this repo.

2. Install necessary dependencies via composer.
```
composer install
```

3. Zip the plugin with all dependencies installed.
```
zip -r AuthOpenIDConnect AuthOpenIDConnect/*
```

4. Install the plugin in LimeSurvey and fill in the necessary settings in order to connect to your ID Provider.

## Credits
Thanks to Michael Jett for providing the [OpenID Connect Client](https://github.com/jumbojett/OpenID-Connect-PHP)!
