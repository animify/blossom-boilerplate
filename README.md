# Blossom UI Boilerplate
Get started with Blossom UI basics using this starter boilerplate.

Blossom UI is a Stylus environment for developers to theme their website; already consisting of several vital web elements, it's dead easy for beginners to set up websites within minutes. More advanced users can take advantage of Blossom's theming capabilities using Stylus.

[Find out more about Blossom](http://getblossom.io/ "Blossom UI")

### Features
- Stylus powered Blossom framework for CSS
- PugJS for HTML templating
- Hot reloading of CSS and HTML content using Browser Sync
- Production & Development environments
- JS file minifier
- HTML compression
- Image optimization
- CSS compression
- Detailed Gulp CLI debug

### Setup
Download or clone the repository to your directory of choice.

Install all the dependencies: `npm install`

If you have problems using Gulp, make sure it's in the working directory: `npm install gulp`

### Development environment
Run `gulp dev` to start the Browser-Sync server on port: 3000.

To make sure you've run it correctly ensure there are no fatal errors in the console, and finally navigate to `http://localhost:3000` to view the page.

If you see `It's working!`, then you're good to go!

Changes made to a Blossom `.styl` or Template `.pug` file will be stream loaded back in to your browser.

### Production environment
Running `gulp prod` will handle everything you need to just drag the `dist` file straight into the hosting of your choice.

This includes:
- All HTML files deflated from whitespace
- Uglified JS files
- Compiled & compressed Blossom UI `.css` file
- Image (.png/.jpg/.jpeg/.gif) optimization

### Modifying Blossom
Modifying Blossom UI is dead easy. Just navigate to `./libs/stylus` and you'll be greeted by the Stylus source contents.

You can edit the existing design of Blossom by overriding `.styl` files in `src` and input custom styling in `_.styl`.

###### Make sure to make use of/change variables in `variables.styl`

### Hosting
The main purpose of this boilerplate is to output static files which is compatible with the majority of hosting services out there.

My hosting of choice for static files is [Surge](http://surge.sh)

#### Get hosting

Install Surge: `npm install --global surge`

Build the boilerplate to the `dist` folder: `gulp prod`

Upload to Surge: `surge ./dist`

[Find out more about getting started with Surge here](http://surge.sh/help/getting-started-with-surge)

### Issues
If you find any issues with running or building the boilerplate on certain machines open up an issue

Licensed under MIT - Copyright (c) 2017
