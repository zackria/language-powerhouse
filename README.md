# PowerHouse® 4GL language package

Provides support for syntax coloring in the Atom text editor.


# Publish the package
`apm publish minor`

`apm publish version-type`

`apm publish --tag v0.0.1 minor`

:note: `version-type can be major, minor and patch.`

## First Time Publishing

`git checkout -b master`

`git push -u origin master`

`apm publish minor`

#### Reference
[language-scilab](https://github.com/JeremyHeleine/language-scilab/)

[atom-language-powerhouse](https://atom.io/packages/search?q=language-powerhouse)

├── CHANGELOG.md
├── LICENSE.md
├── README.md
├── keymaps
│   └── my-package.json         <- Key shortcuts registered by your package
├── lib
│   ├── my-package-view.js
│   └── my-package.js           <- Entry point of your package
├── menus
│   └── my-package.json         <- Menus declaration of your package into Atom application
├── package.json                <- Description and library dependencies of your package
├── spec                        <- Tests directory (Jasmine) of your package
│   ├── my-package-spec.js
│   └── my-package-view-spec.js
└── styles                      <- Stylesheets used by your package
└── my-package.less
