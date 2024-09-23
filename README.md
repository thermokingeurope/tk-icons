# tk-icons

_1.1.1_

## Introduction

This package provides the custom web-font TK Icons, designed for exclusive use across Thermo King’s network of sites and applications. The icon set is tailored specifically for Thermo King’s internal and external platforms to ensure consistency and ease of use across various interfaces.

## Available Icons

This package currently includes the following icons:

    •	Temperature (Three Quarters): \f2c8
    •	Sun: \f185
    •	Arrow Left: \f060
    •	Arrow Up: \f062
    •	Arrow Down: \f063
    •	Arrow Left Long: \f177
    •	Globe: \f0ac
    •	Envelope: \f0e0
    •	Bell: \f0f3
    •	Magnifying Glass: \f002
    •	Square Xmark: \f2d3
    •	Snowflake: \f2dc
    •	Location Dot: \f3c5
    •	User: \f007
    •	House: \f015
    •	Arrow Right: \f061
    •	User with Headset: \f82d
    •	Arrow Right Long: \f178

* PHP

## Installation

1. **Install the package**:

   ```
   npm install tk-icons --save
   ```

1. **Import the SCSS**:

   ```
   $tk-icon-font-path: "./path/to/fonts";
   @import 'node_modules/tk-icons/src/scss/_icons.scss';
   ```

### Usage

You can apply the icons to elements using the corresponding class names:

    <i class="tk-icon tk-icon-sun"></i> <!-- Sun Icon -->
    <i class="tk-icon tk-icon-arrow-right"></i> <!-- Arrow Right Icon -->

or using pseudo-elements:

    &:after {
        font-family: 'tk-icon';
        content: "\f061";
    }

## Icon Requests

This package is a work in progress, and more icons will be added over time. If you need a specific icon or have any requests, feel free to reach out.


## Licensing

The use of this icon set is restricted to Thermo King and its affiliates.