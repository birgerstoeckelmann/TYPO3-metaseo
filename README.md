# MetaSEO - Search Engine Optimization for TYPO3

![stable v2.0.0](https://img.shields.io/badge/stable-v2.0.0-green.svg?style=flat)
![development v2.0.0](https://img.shields.io/badge/development-v2.0.0-red.svg?style=flat)
![License GPL3](https://img.shields.io/badge/license-GPL3-blue.svg?style=flat)


[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/mblaschke/typo3-metaseo.svg)](https://isitmaintained.com/project/mblaschke/typo3-metaseo "Average time to resolve an issue")
[![Percentage of issues still open](https://isitmaintained.com/badge/open/mblaschke/typo3-metaseo.svg)](https://isitmaintained.com/project/mblaschke/typo3-metaseo "Percentage of issues still open")


[![SensioLabsInsight](https://insight.sensiolabs.com/projects/19914ab4-1f0f-4be0-9215-410fba880af2/big.png)](https://insight.sensiolabs.com/projects/19914ab4-1f0f-4be0-9215-410fba880af2)


This extension provides an indexed google/xml-sitemap, enhanced metatag-support and pagetitle-manipulations for TYPO3 CMS.
It's a replacement for the "metatag"-extension and the successor of "tq_seo".

* Manual:     https://docs.typo3.org/typo3cms/extensions/metaseo/
* Git:        https://github.com/mblaschke/TYPO3-metaseo
* Support:    https://github.com/mblaschke/TYPO3-metaseo/issues

## Version status

* Version **2.0.0**:

  + Branch **master**
  + TYPO3 Version: 6.2.x - 7.4.x
  + Composer: dev-master

* Version **2.x**:

  + Branch **develop**
  + TYPO3 Version: 6.2.x - 7.4.x
  + Composer: dev-develop

For version specific information see [Changelog for MetaSEO](CHANGELOG.md)


## Composer Support

MetaSEO (stable) is available **from TYPO3 TER** and also available with composer ::

    {
        "repositories": [
            { "type": "composer", "url": "https://composer.typo3.org/" }
        ],
        .......
        "require": {
            "typo3/cms": "6.2.*",
            "typo3-ter/metaseo": "*"
        }
    }

Or (unstable, don't blame me for bugs - but feel free to report bugs) directly **from Github** ::

    {
        "repositories": [
            { "type": "composer", "url": "https://composer.typo3.org/" },
            { "type": "vcs", "url": "https://github.com/mblaschke/TYPO3-metaseo.git" },
        ],
        .......
        "require": {
            "typo3/cms": "6.2.*",
            "mblaschke/metaseo": "dev-master"
        }
    }

## Found a bug? Got problems?

Please send us following information for easier bug hunting:

* MetaSEO version
* TYPO3 version
* PHP version
* Hoster and/or Linux distribution

## Contribution

If you want to contribute make sure you have an Editorconfig-Plugin installed in your IDE.
See [.editorconfig](.editorconfig) for indentation.

This TYPO3 Extension is using [PSR-2](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md) as coding style.
