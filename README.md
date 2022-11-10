
[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/slackero/bootstrap-extension/main/LICENSE) [![NPM Version](https://img.shields.io/npm/v/@slackero/bootstrap-extension)](https://www.npmjs.com/package/@slackero/bootstrap-extension)

# Bootstrap Extension (Forked)

Everything that may be useful but missing in Bootstrap 5.x

**Bootstrap Extension** is originally developed by Peter Joiner — AKK IT, Inc.


## Quick Start

- [Download the latest release](https://github.com/slackero/bootstrap-extension/releases)
- Clone the repo `git clone https://github.com/slackero/bootstrap-extension.git`
- Install with [npm](https://www.npmjs.com/package/@slackero/bootstrap-extension) `npm i @slackero/bootstrap-extension`


## Usage

Include Bootstrap Extensions’s CSS and JS. Place the `<link>` tag in the `<head>` for our CSS, and the `<script>` tag for the JavaScript before the closing `</body>`.
Ensure  [Bootstrap](https://getbootstrap.com/docs/5.2/getting-started/introduction/#quick-start)’s CSS and JavaScript are loaded before.

```html
<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>
            Bootstrap Extension demo
        </title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
        <link href="../css/bootstrap-extension.min.css" rel="stylesheet">
    </head>
    <body>
        <div class="border border-6 border-fresh rounded-6 p-3 bg-cream m-5">
            <h1 class="text-center">
                Bootstrap extension 5.2.1!
            </h1>
        </div>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous"></script>
        <script src="../js/bootstrap-extension.min.js"></script>
    </body>
</html>
```


## Documentation

Visit the original website of Bootstrap extension [bootstrap-extension.com](https://bootstrap-extension.com/).


## Browser Support

Works well with all the browsers [supported by Bootstrap 5.2](https://getbootstrap.com/docs/5.2/getting-started/browsers-devices/)


## FAQS


## Known Issues


## Copyright

Copyright (c) 2018-2022 Peter Joiner — AKK IT, Inc.
