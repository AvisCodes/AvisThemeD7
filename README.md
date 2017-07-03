Avis Drupal 7 theme starter kit.

##Pre-Requirements:

Install nodejs:
````
sudo apt-get install nodejs
````
Install npm:
````
sudo apt-get install npm
````
Install gulp:
````
sudo npm install gulp -g
````
Install bower:
````
sudo npm install -g bower
````
Check:
````
nodejs -v 
npm -v 
gulp -v
````
If issues like absent create symlink:
````
sudo ln -s /usr/bin/nodejs /usr/bin/node
````

##Installation

Simply run
````
npm install
````
and
````
bower install
````
in the directory with package.json and bower.json.

##Commands
Run
````
gulp
````
or
````
npm run gulp
````
if u don't install gulp globally.

The result html will be here
````
src/build/example.html
````

You can see gulp tasks in gulpfile.js.
