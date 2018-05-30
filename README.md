# Udacity RSS Feed Reader Testing app

[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

# Table of contents

- [Project Overview](#project-overview)
- [Installation](#installation)
	- [Live demo](#live-demo)
	- [Local installation](#local-installation)
- [How to use](#how-to-use)
- [Test conducted](#test-conducted)
- [Tools used](#tools-used)
	- [Resources used](#resources-used)
- [Author](#author)
- [Contribution](#contribution)
- [License](#license)

# Project Overview

[(Back to top)](#table-of-contents)

This is a web-based application that reads RSS feeds from [Udacity Blog](http://blog.udacity.com/feed), [CSS Tricks](http://feeds.feedburner.com/CssTricks), [HTML5 Rocks](http://feeds.feedburner.com/html5rocks) and [Linear Digressions](http://feeds.feedburner.com/udacity-linear-digressions). The project was originally made from another developer including the first test but they decided to start their own company.

My role was to use [Jasmine](http://jasmine.github.io/) framework and create some tests ensuring that the app is running error-free.

# Installation

[(Back to top)](#table-of-contents)

## Live demo

You can view a live demo on this [git page](https://markoboy.github.io/FeedReaderTesting/)

## Local installation

- Download the repository from the download button.
- Or clone the repository with Git.
- Open the `index.html` with your browser.
- Check the tests on the bottom of your screen.
- You can edit the `feedreader.js` to experiment with the tests.

# How to use

[(Back to top)](#table-of-contents)

You can use this app to read latest feeds of popular technolgical sites in order to learn and view the latest news.

You can click on the humburger icon and pick the site of your choice. Afterwards, you can click on the feeds titles to navigate to their webpage.

On the bottom of the page, you can see all conducted tests that have passed.

# Test conducted

[(Back to top)](#table-of-contents)

- **RSS Feeds**
	- _check that allFeeds are defined_
	- _that they have a defined URL_
	- _that they have a defined name_
- **The menu**
	- _is hidden by default_
	- _changes visibility when clicked_
- **Initial Entries**
	- _should have at least an entry element_
- **New Feed Selection**
	- _should change the page content_

# Tools used

[(Back to top)](#table-of-contents)

- [*Git version control*](https://git-scm.com/)
- [*Sublime text editor 3*](https://www.sublimetext.com/)
- [*Js Hint*](http://jshint.com/)

## Resources used

[(Back to top)](#table-of-contents)

- **Styles**
	- [Roboto font](https://fonts.google.com/specimen/Roboto?selection.family=Roboto)
	- [normalize.css v3.0.2](git.io/normalize)
	- [Icomoon](https://icomoon.io/)
- **Library**
	- [Jasmine 2.1.2](https://jasmine.github.io/)
	- [JQuery](https://jquery.com/)
	- [Handlebars](https://handlebarsjs.com/)
	- [Google JSAPPI](https://developers.google.com/chart/interactive/docs/basic_load_libs)

# Author

[(Back to top)](#table-of-contents)

- _Test suites_ - [Athanasios Markou](https://www.linkedin.com/in/a-markou/)
- _Initial work_ - [Udacity](https://github.com/udacity/frontend-nanodegree-feedreader)

# Contribution

[(Back to top)](#table-of-contents)

Pull requests are not welcomed, as this is a project to test my skills in unit testing.

# License

[(Back to top)](#table-of-contents)

This project is licensed under the [MIT License](/LICENSE)
