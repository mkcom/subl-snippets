subl-snippets
=============

Some neat snippets for Sublime Text 2.

## ngboot
Creates a simple boilerplate for angular.boostrap. Just type `ngboot` [TAB] in a Javascript file and jump through the tabs.

```
(function (window, angular) { 'use strict';

    angular.element(document).ready(function () {
        angular.bootstrap(document, ['main']);
    });

    angular
        .module('main', [])
        .config(function () {

        })
        .run(function () {

        });

})(window, window.angular);
```

## ngctrl
Creates a simple boilerplate for an angular controller. Just type `ngctrl` [TAB] in a Javascript file and jump through the tabs.

```
(function (window, angular) { 'use strict';

    angular.module('main')
    .controller('Ctrl', function () {

    });

})(window, window.angular);
```

(tbc)