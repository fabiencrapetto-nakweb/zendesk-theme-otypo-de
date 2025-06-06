# Copenhagen Theme Customization for Zendesk Help Center

This project is a customized version of the **Copenhagen** theme, the default and free theme provided by Zendesk for Help Centers.

## Overview

The Copenhagen theme offers a clean and accessible design for Zendesk Guide. This customization builds on the original theme to better align with specific brand, functionality, or UX requirements.

## What's Included

- Modifications to styles (CSS/SCSS)
- Custom JavaScript for improved interactivity
- Template updates (HTML/Handlebars)
- Additional assets (icons, images, etc.)

## Getting Started

To use or continue editing this theme:

1. Download the source files or clone this repository.
2. Run `npm install zcli -g` to install the command line if not already done
3. Run `zcli login -i`and follow the steps
    - Subdomain :`otypode`
    - Email : *see Dashlane **Zendesk Theme Credentials***
    - Token :  *see Dashlane **Zendesk Theme Credentials***
4. Run `zcli theme preview` to test locally.

To publish, you will need to go through a specific way : 
1. In Zendesk Help Center admin, go to the `/theming/workbench` page
2. Find the theme with name `Copenhagen - Custom Theme` and open its contextual menu.
3. Click on `Update from Github`

## Notes

- Based on the official **Copenhagen** theme from Zendesk.
- All customizations are fully compatible with the Zendesk Guide templating framework.

## License

Original Copenhagen theme © Zendesk, Inc. – [MIT License](https://github.com/zendesk/copenhagen_theme/blob/main/LICENSE).
Customizations in this repository are also provided under the MIT License unless otherwise stated.
