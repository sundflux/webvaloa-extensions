webvaloa-extensions
========

Webvaloa extensions package.

## Installation

This package is part of Webvaloa platform.

```json
{
    "require": {
        "sundflux/webvaloa-extensions": "^3.0.0"
    }
}
```

## Requirements

- PHP 7.2.19 or newer.

## Features

- 

## Copyright and license

Copyright (C) 2019 Tarmo Alexander Sundström & contributors.

Libvaloa is licensed under the MIT License - see the LICENSE file for details.

## Contact

- http://www.webvaloa.com/

## Change Log
All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](http://semver.org/).

Changes are grouped by added, fixed or changed feature.

### [3.0.6] - 2019-09-08
- Always write component version to component table when installing component.

### [3.0.5] - 2019-09-08
- Separate role creation to installRoles()

### [3.0.4] - 2019-09-07
- Write versioning to component table.

### [3.0.3] - 2019-09-06
- Fix Exception catch.

### [3.0.2] - 2019-09-06
- Don't automatically run installModels() inside install().
- Add missing db connection to Table model create().

### [3.0.1] - 2019-09-05
- Assign roles from manifest.yaml when installing component.

### [3.0.0] - 2019-09-02
- First version separated from Webvaloa main repository as a package. 

