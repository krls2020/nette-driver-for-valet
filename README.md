# Nette Framework Support for Laravel Valet

This repository contains a custom driver for Laravel Valet, allowing it to seamlessly support Nette Framework
applications. Laravel Valet is a development environment for macOS designed to simplify local web development. However,
it's primarily optimized for Laravel projects.

With this custom driver, you can now use Valet to serve Nette Framework applications with ease. It intelligently detects
Nette-specific files like `app/Bootstrap.php` and `config/common.neon`, ensuring a smooth experience for your Nette
projects.

## Quick Setup

1. Place the `NetteValetDriver.php` file in your Valet custom drivers directory, typically located
   at `~/.config/valet/Drivers`.
2. After adding the driver, restart Valet by running `valet restart` in your terminal
3. Start serving Nette Framework projects using Valet.

## System Compatibility

Driver has been tested on macOS Ventura and 
