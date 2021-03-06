# BlackCoffee


##A flatiron http server template in coffee-script 
###based on [iron-coffee](https://github.com/twilson63/iron-coffee) 
by [Tom Wilson](https://github.com/twilson63/)

###[Fork black-coffee on Github](https://github.com/gradus/black-coffee)

## About

[Black Coffee](https://github.com/gradus/black-coffee) is a template or boiler-plate to get started writing flatiron web applications in CoffeeScript.

It includes a Cakefile that lets you build, and watch your coffeescript as you develop.

Just hack away at app.coffee in the src directory and create your own
pages.  [Skeleton CSS framework](http://www.getskeleton.com/) is included as well as a default skeleton page. 

The default CoffeeCup templates for black-coffee are located in the src/pages directory.  3 pages and a layout template are included as examples in addition to the skeleton page.

Assets can be served from the 'assets' directory using [ecstatic](https://github.com/jesusabdullah/node-ecstatic).

####Example Website

[Drink your Black Coffee](http://black-coffee.jit.su)

---
## Technologies
This template uses the following to create nodejs applications 

* [Node v0.6.14](http://nodejs.org/)
* [Flatiron](http://flatironjs.org/)
* [CoffeeScript v1.3.1](http://coffeescript.org/)
* [CoffeeCup Master](https://github.com/gradus/coffeecup)
* [Creamer](https://github.com/twilson63/creamer)
* [node-ecstatic](https://github.com/jesusabdullah/node-ecstatic)
* [Skeleton](http://www.getskeleton.com/)

---
## Getting Started

#### Install [nodejs and npm](http://nodejs.org/)


    git clone http://github.com/gradus/black-coffee.git [project-name]
    cd [project-name]
    npm install .

This is just a template to get you started.

If you want to make this your own project on github:

    git remote rm origin
    git remote add origin git@github.com:[your github accountname]/[project-name].git

#### Dependencies

    npm install .
    npm install flatiron

Black-Coffee currently requires the master version of director

    cd node_modules/flatiron
    npm uninstall director
    npm install git://github.com/flatiron/director.git
    cd ../../

#####Build

    cake build

#####Watch

    cake watch

#####Test
write tests, put them in the test directory and run

    cake test

##### Run

    npm start

---
## Thanks

* [Tom Wilson](https://github.com/twilson63) for creating iron-coffee
* [Jeremy Ashkenas](https://github.com/jashkenas) for creating coffee-script
* [Nodejitsu](https://github.com/nodejitsu) for creating flatiron

