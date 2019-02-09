# Chrome-Extension-Template
-
A template to build Chrome Extension that uses npm modules.
Scripts in Chrome-Extension must be a single file(single file for each script in manifest.json) so you can not use npm modules 
in your code.
this template uses webpack to build single .js file in src.o directory

|##USAGE:
-
clone this repository by :

`git clone https://github.com/payamnaghdy/Chrome-Extension-Template.git`

install dev dependecies whit:

`npm install`

Chrome Extension sources will be in app directory
write your javascript app in src
then run `npm run-script build` to put your js components together in app/src.o/background.js and if you want webpack watching your code just use `npm run-script watch`

2to use npm modules: `require('module-name')`
                                                                                                                                                                                                                   
                                            
