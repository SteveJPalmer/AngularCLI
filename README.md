# Extend Angular CLI for Lodash, Modernizr &amp; lite-server

## Integrate: Lodash
_cf files:_  package.json,
             @types/lodash,
             app.component.ts (ngOnInit)
             
             
## Integrate: Modernizr
_cf files:_  package.json
             ./assets/modernizr.js,
             @types/modernizr, 
             tsconfig.app.js ("types"),
             angluar-cli.json ("scripts"),
             app.component.ts (ngOnInit)


## Integrate: lite-server
replacement for in-memory webpack-Dev-Server - can view ./dist build files

1st terminal - CLI Build with watch 

`ng build --watch`

2nd terminal - Http Server with watch and live-refresh _(default)_

`node_modules\.bin\lite-server --baseDir=".\dist"`

_or via script:_ `npm run lite-server`
