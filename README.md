# fnc-seed
This is an empty fncJS based Web app. You can use it to quickly bootstrap your application.
Since fncJS does not dictate the structure of your application, you can use this application as a seed for any Web application project.

It provides a skeleton to create a Web app using Web Components.

## Getting Started
Clone fnc-seed

Clone the fnc-seed repository using [git][git]:

```
git clone https://github.com/itinora/fnc-seed.git
cd fnc-seed
```

### Install npm and gulp tools

Install npm to get bower and gulp dependencies

```
cd dev
npm install
```

This will create folder `node_modules` that contains all tools to run gulp tasks

### Install bower components

Run gulp tasks to install bower components

```
gulp bower
```

This will create folder `bower_components` that contains all client side dependencies

### Run application

```
gulp
```

This will run the application and watch files for changes. Whenever any file is modified BrowserSync will auto refresh the page



