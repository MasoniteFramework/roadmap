# Masonite Roadmap

> The purposes of the roadmap is to let everyone understand the direction the framework is heading in both the short term and long term.
We will explain a general planned feature and a small bit of explanation of needed.

## v2.1 -- [December 2018]

- [x] Move more code into core by inheriting from some parent class instead of putting the entire class in the framework installation
- [x] Move more framework features into core middleware. There is a lot of code inside the `RouteProvider` that can be abstracted out and put into middleware
- [x] Use better PEP 8 standards. For 2.0 we left triple single quotes in (`'''` instead of `"""`) which is not PEP 8 compliant but I (Joe Mancuso) 
thought it looked cleaner. Now I think we should deff do PEP 8 more.
- [x] Docstring all the code and generate a static site to host the API reference documentation.
- [x] General code cleanup and abstractions to make the codebase more easy to contribute to.
- [x] Add out of the box support for seeding (have base files setup)
- [x] Create an official package for unit testing a Masonite app

- [x] Full video course
- [x] Remove resolving of parameters
- [x] Make pipenv the official package management tool

## v2.2 -- [June 2019 LTS]

- [ ] 2yr bug release, 3yr security release
- [ ] More code cleanup from hotfixes and various bug fixes from 2.1
- [ ] Slight file system changes. nothing really planned about this but any file system changes should be brought up in slack and attached to this release.
- [ ] Slight API changes that won't fit in a minor but needs to be able to be up to date for the next 3 years.
- [ ] Create a wsgi service for Masonite and other WSGI apps.
- [ ] full selenium testing package plus command testing
- [ ] Better publishing of packages 
- [ ] Create a logging package with at least 3 drivers: native python logger, logstash and sentry.
- [ ] Create an official website to host user accounts, information, blogs, videos and 

## v3.0 -- [December 2019]
- [ ] Remove all modules from Masonite container
- [ ] Remove the dependence on any key bindings so all bindings can be "simple"
- [ ] change `resources/templates` to `resources/views`
