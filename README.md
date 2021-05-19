# TMDb Movie Search


TMDb Movie Search is a responsive app that utilises Twitter's [typeahead.js](https://twitter.github.io/typeahead.js/) and [Bloodhound](https://github.com/twitter/typeahead.js/blob/master/doc/bloodhound.md) suggestion engine, loading data via [The Movie Database (TMDb) API](https://www.themoviedb.org/documentation/api).



## Tools
Key tools used in this React project are:

| Tool             | Description   |
| :-------------:|--------------|
| [React](http://facebook.github.io/react/index.html) | A JavaScript library for building user interfaces |
| [Typeahead.js](https://twitter.github.io/typeahead.js/) | A flexible JavaScript library that provides a strong foundation for building robust typeaheads |
| [Bloodhound](https://github.com/twitter/typeahead.js/blob/master/doc/bloodhound.md) | Bloodhound is the typeahead.js suggestion engine |
| [Bootstrap](http://getbootstrap.com/) | Build responsive, mobile-first projects on the web with the world's most popular front-end component library |
| [SASS](http://sass-lang.com/) | 	Sass is the most mature, stable, and powerful professional grade CSS extension language in the world |
| [Browserify](http://browserify.org/) | Browserify lets you `require('modules')` in the browser by bundling up all of your dependencies |
| [Babel](https://babeljs.io/) | Use next generation JavaScript, today |
| [Gulp](http://gulpjs.com/) | Gulp is a toolkit for automating painful or time-consuming tasks in your development workflow |


1. `cd reactjs-tmdb-app`
2. Install packages: `npm install` and `bower install`
3. Build project and launch: `gulp watch`
4. Open your browser at: `http://localhost:9000`

## Browser Support
This project makes usage of the Fetch API, utilising a polyfill for older browsers.

- Chrome 42+
- Firefox 39+
- Safari 10+ (with polyfill)
- Internet Explorer 11+ (with polyfill)
- Edge 14+

## Node.js
Supports LTS version (v6).


