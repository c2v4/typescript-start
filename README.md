#Typescript start
This is a project serving as a template for starting typescript web application. All neccessary configurations is already here. Just clone repo and start writing awesome typed code!


Prerequisites:
* npm installed
* install packages globally:
npm install -g gulp tsd typescript

In order to start run in the root directory:
* typings install
* npm install
* gupl serve

Leave the console with `gulp serve` running and change the files within.

When you want to add a js library run the following:
* `npm install --save library_name`
* `typings install --save library_name`
If the typings were not found, you could try with:
* `typings install --source dt --save library_name`

Modify files under src directory. Directory src/js serves as a transpiler output directory. Typescript files should be stored under src/app directory.
If you want to change project meta data, change it in package.json file.