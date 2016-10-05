# System Stream Wrappers

## Description

Provides stream wrappers to access module, theme, profile, and library files 
and directories. Note these stream wrappers are read-only as none of these 
files or directories should be writable by your webserver.

## Installation

Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

## Example usage

 - module://file/icons/text-plain.png
 - theme://bartik/screenshot.png
 - theme://default/logo.png
 - profile://minimal/minimal.info
 - profile://current/standard.info (profile://current expands to the active 
 profile for the site)
 - library://ckeditor/images/spacer.gif (works only if the Libraries module 
 is enabled)

##Issues

Bugs and Feature requests should be reported in the
[Issue Queue](https://github.com/backdrop-contrib/system_stream_wrapper/issues)

##Current Maintainers

- [Laryn Kragt Bakker](https://github.com/laryn) - [CEDC.org](https://cedc.org)

##Credits

- Ported to Backdrop CMS by [Laryn Kragt Bakker](https://github.com/laryn) - [CEDC.org](https://cedc.org).
- Maintained for Drupal by [Dave Reid](https://github.com/davereid) and [Andrew Barry](https://github.com/deviantintegral).
- Drupal module supported by Palantir.net and Lullabot.

##License

This project is GPL v2 software. See the [LICENSE.txt](https://github.com/backdrop-contrib/system_stream_wrapper/blob/1.x-1.x/LICENSE.txt) file in this directory for
complete text.
