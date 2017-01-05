# bower-package

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.15.1.

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.

## Steps
* clone the project
* npm install
* bower intsall

this project uses grunt and bower.. so better insatlla them earlier.
install grunt-cli instead grunt

then `npm update` to update npm libraries.. beacuase few versions were depricated.

for some reason angular 1.6 has some issues with routing.. so hard setting to 1.5.8

some thing related to karma, phantom-js not working in yeoman generated libraries.. so reinstall them using below command.
`npm install grunt-karma karma karma-phantomjs-launcher karma-jasmine jasmine-core phantomjs-prebuilt --save-dev`


Warning:

`include.preload.js:468 Calling Element.createShadowRoot() for an element which already hosts a shadow root is deprecated. See https://www.chromestatus.com/features/4668884095336448 for more details.`

i observed above warning when ad blockers are enabled