awesome-rack
===============

> A curated list of awesome Ruby rack, middlewares, frameworks and web servers

# Contents

- [General](#general)
- [Tutorials](#tutorials)
- [Presentations](#presentations)
- [Videos](#videos)
- [Web Servers](#web-servers)
- [Frameworks](#frameworks)
- [Middlewares](#middlewares)
- [Helpers and Tools](#helpers-and-tools)
- [Miscellaneous](#miscellaneous)
- [Inspiration](#inspiration)

## General

* [Rack](http://rack.github.io/) - Ruby Rack Official website
* [rack-contrib](https://github.com/rack/rack-contrib) - Contributed Rack Middleware and Utilities
* [Rack Spec](http://www.rubydoc.info/github/rack/rack/file/SPEC) - Rack Interface Specification
* [Rack Wiki](https://github.com/rack/rack/wiki) - has a list of tutorals, presentations and middlewares.
* [Rack Documentation](http://www.rubydoc.info/github/rack/rack/) - Rack Reference Documentation    
* [the_metal](https://github.com/tenderlove/the_metal) - A spike for thoughts about Rack 2.0
* [Rack Development](https://groups.google.com/forum/#!forum/rack-devel) - Rack Development list (Google Group)
    
## Tutorials

* [Introducing Rack](http://chneukirchen.org/talks/euruko-2007/neukirchen07introducingrack.pdf) by Christian Neukirchen - 
  An overview of Rack interface and the Rack gem.
* [A Quick Note on Rack](http://www.ralphonrails.com/rack/2015/07/05/a-quick-note-on-rack.html)   
* [Concisely about Rack applications](http://zaiste.net/2012/08/concisely_about_rack_applications/)
* [Exploring Rack](http://code.tutsplus.com/tutorials/exploring-rack--net-32976)
* [Rack basics](http://albertogrespan.com/blog/rack-basics/) - Covers basic usage of Response, ERB template and the `rackup` tool.
* [Rack Authentication Middleware](http://codefol.io/posts/Rack-Authentication-Middleware)
* [Rack middleware](http://albertogrespan.com/blog/rack-middleware/) - Create two simple middlewares and glue it all together using `Rack::Builder`
* [What is Rack, please?](http://southdesign.de/blog/rack.html)
* [Rack from the ground up](https://thisdata.com/blog/rack-from-the-ground-up/)
* [Creating Static Sites in Ruby with Rack](https://devcenter.heroku.com/articles/static-sites-ruby) - and deploy to Heroku.
* [Writing a Small DSL Using Rack](http://nick-aschenbach.github.io/blog/2015/02/21/a-small-dsl-rack-app/)
* [A simple Ruby Rack router](https://erikeldridge.wordpress.com/2010/02/21/simple-ruby-rack-router/) - a simple router in 17 lines of code
* [Understanding Rack Builder](http://ixti.net/development/ruby/2011/09/03/understanding-rack-builder.html)
* [Getting Started with Rack](https://gist.github.com/markbates/4240848) - use Rack::Builder to create a simple framework that
  handles HTTP GET requests.
* [Understanding Rack Apps and Middleware](https://blog.engineyard.com/2015/understanding-rack-apps-and-middleware)
* [Make Your Own Rack Server](http://www.blrice.net/blog/2015/05/31/make-your-own-rack-server/)
* [Testing Rack-based APIs with Cucumber and RSpec](http://hackers.lookout.com/2014/01/testing-rack-based-apis-with-cucumber-and-rspec/)    
* [Rails on Rack](http://guides.rubyonrails.org/rails_on_rack.html) - Covers Rails integration with Rack and interfacing with other Rack 
  components. This guide tells you how to use Rack Middlewares in your Rails applications, Action Pack's internal Middleware stack and
  how to define a custom Middleware stack.
* [IT'S ONLY RACK ON RAILS BUT I LIKE IT](http://pathfindersoftware.com/2009/02/its-only-rack-on-rails-but-i-like-it/)
* [Jesse Newland / Rails Metal: a micro-framework with the power of Rails](http://jnewland.github.io/articles/2008/12/16/rails-metal-a-micro-framework-with-the-power-of-rails-m/)
* [Asynchronous responses in Rack](http://polycrystal.org/posts/2012-04-14-async-rack.html)
* [Building Streaming REST APIs with Ruby](http://www.intridea.com/blog/2012/5/24/building-streaming-rest-apis-with-ruby)
* [Rack Developer's Notebook by Bala Paranj](http://files.meetup.com/437842/RackDevelopersNotebook.pdf)
* [Let's Build a Sinatra (2015)](https://robots.thoughtbot.com/lets-build-a-sinatra)    
* [EBook: Build Your Own Sinatra by K-2052 (2015)](http://buildyourownsinatra.com/)   
* [Book: Rebuilding Rails by Noah Gibbs (2013)](https://rebuilding-rails.com/)

## Presentations

* [Introducing Rack by Christian Neukirchen at EuRuKo 2007](http://chneukirchen.org/talks/euruko-2007/chneukirchen-euruko2007-introducing-rack.pdf) - An 
  overview of Rack interface and the Rack gem.
* [Rack and Middleware by Tim Uruski 2015/Feb](https://speakerdeck.com/timuruski/rack-and-middleware)
* [8 Minutes on Rack](http://www.slideshare.net/danwrong/8-minutes-on-rack-presentation) - The basic introduction to the Rack application definition.
* [Using and scaling Rack and Rack-based middleware by alony](https://speakerdeck.com/alony/rack)
* [Rack talk by Caleb Woods](http://www.calebwoods.com/rack-talk/) - A overview of essential Rack built-in middlewares and rack in Rails. 
* [Building Web Apps with Rack and Sinatra by Tom Black](https://speakerdeck.com/blacktm/building-web-apps-with-rack-and-sinatra)
* [Sinatra and friends by Jiang Wu](http://www.slideshare.net/jiang.wu/sinatra-and-friends)
* [Building Web Services (HTTP APIs) with Ruby and Sinatra](http://slideshow-s9.github.io/demos/sinatra_http_api2.html)
* [Ruby on Rack Small Talk by Meagan Waller](https://speakerdeck.com/meaganewaller/ruby-on-rack-small-talk) - builds an example that
  implements tiny MVC and a simple router. The example is available on [GitHub](https://github.com/meaganewaller/ruby-on-rack-example) 
* [Rack: A Framework to roll your own by Nishant Modak](https://speakerdeck.com/nishantmodak/rack-a-framework-to-roll-your-own)
* [Ruby MVC from scratch with Rack](https://speakerdeck.com/donschado/ruby-mvc-from-scratch-with-rack) - WOW! The example code is 
  available on the GitHub repo [Frack-MVC](https://github.com/DonSchado/Frack-MVC)
* [Building web framework with Rack](http://www.slideshare.net/sickill/building-web-framework-with-rack)  
* [Constructing Web APIs with Rack, Sinatra and MongoDB by Oisin Hurley](http://www.slideshare.net/oisin/constructing-web-apis-with-rack-sinatra-and-mongodb)
* [Streaming APIs with Ruby by Jerry Cheung](https://speakerdeck.com/jch/streaming-apis-with-ruby)
* [Middleware: A General Purpose Abstraction by Mitchell Hashimoto](https://speakerdeck.com/mitchellh/middleware-a-general-purpose-abstraction) 
* [High Performance Rails (long edition) by Issei Naruta](https://speakerdeck.com/mirakui/high-performance-rails-long-edition) - Rails 
  Performance tuning and how to do profiling and caching.
* [A Rails App in a Single Rackup File by Ryan Alyea](http://rofish.net/rails_single_file.pdf)  
* [Rack - rolling your own, tiny like, web thingoes by Ryan Allen](http://yeahnah.org/files/rack-presentation-oct-07.pdf) - talks about concurrency. 

## Videos

> Videos from Railscasts

* [Railscasts Pro #53 Handling Exceptions (revised)](http://railscasts.com/episodes/53-handling-exceptions-revised)
* [Railscasts --- #150 Rails Metal](http://railscasts.com/episodes/150-rails-metal)
* [Railscasts Pro #150 Rails Metal (revised)](http://railscasts.com/episodes/150-rails-metal-revised)
* [Railscasts Pro #151 Rack Middleware](http://railscasts.com/episodes/151-rack-middleware)
* [Railscasts --- #161 Three Profiling Tools](http://railscasts.com/episodes/161-three-profiling-tools)
* [Railscasts Pro #222 Rack in Rails 3](http://railscasts.com/episodes/222-rack-in-rails-3)
* [Railscasts Pro #247 Offline Apps Part 1](http://railscasts.com/episodes/247-offline-apps-part-1)
* [Railscasts Pro #248 Offline Apps Part 1](http://railscasts.com/episodes/248-offline-apps-part-2)
* [Railscasts --- #260 Messaging with Faye](http://railscasts.com/episodes/260-messaging-with-faye)
* [Railscasts --- #271 Resque](http://railscasts.com/episodes/271-resque) - `Rack::Auth::Basic` is used in this Episode
* [Railscasts --- #272 Markdown with Redcarpet](http://railscasts.com/episodes/272-markdown-with-redcarpet)
* [Railscasts Pro #294 Playing with PJAX](http://railscasts.com/episodes/294-playing-with-pjax)
* [Railscasts Pro #305 Authentication with Warden](http://railscasts.com/episodes/305-authentication-with-warden)
* [Railscasts Pro #317 Rack App from scratch](http://railscasts.com/episodes/317-rack-app-from-scratch)
* [Railscasts Pro #319 Rails Middleware Walkthrough](http://railscasts.com/episodes/319-rails-middleware-walkthrough)
* [Railscasts Pro #321 HTTP Caching](http://railscasts.com/episodes/321-http-caching)
* [Railscasts --- #348 The Rails API Gem](http://railscasts.com/episodes/348-the-rails-api-gem)
* [Railscasts Pro #349 Rails Modularity](http://railscasts.com/episodes/349-rails-modularity)
* [Railscasts --- #352 Securing an API](http://railscasts.com/episodes/352-securing-an-api)
* [Railscasts Pro #357 Adding SSL](http://railscasts.com/episodes/357-adding-ssl)
* [Railscasts --- #368 MiniProfiler](http://railscasts.com/episodes/368-miniprofiler)
* [Railscasts Pro #395 Action Controller Walkthrough](http://railscasts.com/episodes/395-action-controller-walkthrough)
* [Railscasts Pro #399 Autocomplete Search Terms](http://railscasts.com/episodes/399-autocomplete-search-terms)
* [Railscasts Pro #414 Batch API Requests](http://railscasts.com/episodes/414-batch-api-requests)

> Videos from other source

* [Tekpub: Understanding Rack](https://www.youtube.com/watch?v=iJ-ZsWtHTIg)
* [Using RSpec with Rack](https://www.youtube.com/watch?v=FV6AQEKxBOg)
* [Code School - Scaling Rails Applications: Advanced HTTP Caching (Episode #10)](https://www.youtube.com/watch?v=2UvpMhzkktw) - 
  talks about max-age, etags, last_modified and Reverse Proxy caches. 
* [Code School - Scaling Rails Applications: Rack & Metal (Episod #13)](https://www.youtube.com/watch?v=P0aOYjoH594)
* [Rack Middleware as a General Purpose Abstraction by Mitchell Hashimoto](https://www.youtube.com/watch?v=i6pyhq3ZvyI)
  * the slide is available on [speakdeck](https://speakerdeck.com/mitchellh/middleware-a-general-purpose-abstraction).
  * [Generalized middleware implementation for Ruby by Mitchell Hashimoto](https://github.com/mitchellh/middleware) - ~ 130 LOC
* [Faking Sinatra with Rack and Middleware by Charles Wood](https://www.youtube.com/watch?v=uH4H5GQOSqQ)
* [Rails Conf 2013 You've got a Sinatra on your Rails by José Valim](https://www.youtube.com/watch?v=TslkdT3PfKc) - Great look 
  at how Rails uses Rack internally  

## Web Servers

> Rack includes handlers for these web servers:

* [WEBrick](https://github.com/ruby/ruby/tree/trunk/lib/webrick) - WEBrick is an HTTP server toolkit that can be configured as an HTTPS 
  server, a proxy server, and a virtual-host server. It is now part of Ruby standard library for Ruby 1.9.3.
* FCGI
* [CGI](https://github.com/ruby/ruby/tree/trunk/lib/cgi) - The Common Gateway Interface (CGI) is a simple protocol for passing 
  an HTTP request from a web server to a standalone program, and returning the output to the web browser
* SCGI
* [Thin](https://github.com/macournoyer/thin/) - Tiny, fast & funny HTTP server. Glues together 3 of the best Ruby libraries: 
  The `Mongrel` parser, `Event Machine` network I/O library and `Rack`, a minimal interface between webservers and Ruby frameworks
* [LiteSpeed](https://www.litespeedtech.com/products/litespeed-web-server/overview) - LiteSpeed Web Server (LSWS) is a high-performance
  Apache drop-in replacement, a commercial web server.

> These web servers include Rack handlers in their distributions:

* [Rouge](https://github.com/guilleiguaran/rogue) - minimal and fast HTTP 1.1 server for Rack applications, powered by `EventMachine`, Ryan Dahl's 
  `http-parser(https://github.com/joyent/http-parser)` and `Rack::Builder`
* [Ebb](https://github.com/gnosek/ebb) - A small and fast web server specifically for hosting dynamic web applications.
* [Fuzed](https://github.com/KirinDave/fuzed-old) - An integrated replacement for Mongrel+Revproxy systems in erlang 
* [GlassFish v3](https://java.net/projects/glassfish/sources/svn/show/trunk/main) - an open-source application server project 
  started by Sun Microsystems for the Java EE platform and now sponsored by Oracle Corporation
* [Phusion Passenger](https://github.com/phusion/passenger) - A web server and application server, designed to be fast, robust 
  and lightweight. Supports Ruby, Python, Node.js and Meteor, and is being used by high-profile companies such as Apple, 
  Pixar, New York Times, AirBnB, Juniper etc as well as over 350.000 websites. Phusion Passenger 5 (codename "Raptor")  has 
  an innovative and optimized HTTP engine, making it up to 4x faster than Unicorn, up to 2x faster than Puma and up to 2x faster 
  than Torquebox. 
* [Puma](https://github.com/puma/puma) - A simple, fast, threaded, and highly concurrent HTTP 1.1 server writtern in Ruby.
* [Reel](https://github.com/celluloid/reel) - A fast, non-blocking "evented" web server written in Ruby. You'll need 
  [reel-rack](https://github.com/celluloid/reel-rack), a Rack adapter for Reel. Reel uses [Celluloid](https://github.com/celluloid/celluloid), an
  Actor-based concurrent object framework for Ruby.  When you create new instances of a class, they're actually concurrent objects, each running
  * [Reel::DSL](https://github.com/celluloid/reel-dsl/) - Minimalist Reel CRUD/WS/SSE endpoint routing. Supports URI-based HTTP/S requests, and Web Sockets
   & Server Sent Events. Influenced by Angelo and Sinatra.
  * [Angelo](https://github.com/kenichi/angelo) - Sinatra-like DSL for Reel that supports WebSockets and SSE
    in their own thread, called "cells" (or actors). Angelo uses Celluloid, Celluloid::IO. Angelo replaces 
    [Sinatra::Synchrony](https://github.com/kyledrake/sinatra-synchrony) which is a very small extension for Sinatra Powered by EventMachine and EM-Synchrony
    that dramatically improves the concurrency of your web application. 
* [Unicorn](http://bogomips.org/unicorn.git) - Rack HTTP server for fast clients and Unix. Mostly wriiten in pure Ruby. Provides `unicorn` - 
  a rackup-like command to launch the Unicorn HTTP server (it uses Rack::Builder DSL) and `unicorn_rails` - a script/server-like command 
  to launch the Unicorn HTTP server
* [unixrack](https://github.com/brightroll/unixrack) - A ruby RACK webserver only for unix using the old unix style. (~500 LOC)
* [uWSGI](https://github.com/unbit/uwsgi) - uWSGI application server container written in Python. Supports Python (WSGI), 
  Ruby (Rack), Perl (PSGI), Lua (WSAPI), PHP (CGI), JVM (JWSGI), Mono (ASP.NET plugin), GO (GCCGO), CGI Scripts.
* [yahns](http://yahns.yhbt.net/) - sleepy, multi-threaded, non-blocking application server for Ruby
* [YARS](https://github.com/ianks/yars) - A server for your (Rack) apps.  
* [Goliath](https://github.com/postrank-labs/goliath) - a non-blocking Ruby web server framework. Bare metal performance, 
  Rack API and middleware support, simple configuration, fully asynchronous processing, and readable and maintainable code.
  The framework is powered by an EventMachine reactor, a high-performance HTTP parser and Ruby 1.9+ runtime. 
* [Mongrel](https://github.com/mongrel/mongrel) - A HTTP library and web server written in Ruby. What makes Mongrel so fast is the 
  careful use of an Ragel extension to provide fast, accurate HTTP 1.1 protocol parsing. (deprecated)
* [Mongrel2](https://github.com/mongrel2/mongrel2) - An application, language, and network architecture agnostic web server 
  that focuses on web applications using modern browser technologies. Written in C.  
* [Pow](https://github.com/basecamp/pow) - zero-config Rack server for Mac OS X. Have it serving your apps locally in under 
  a minute. A Linux fork is availble [here](https://github.com/ysbaddaden/pow).
* [nack](https://github.com/josh/nack) - nack is a Rack server built on top of the Node.js HTTP server  
* [Gorack](https://github.com/gmarik/gorack) - a Go backed frontend webserver for Ruby's Rack applications, inspired by Node's 
  [nack](http://github.com/josh/nack)      
* [Mizuno](https://github.com/matadon/mizuno) - Jetty-powered running shoes for JRuby/Rack. A Rack server for JRuby.  It uses the embeddable Jetty 
  Java servlet container. Mizuno also supports asynchronous request handling, via the Java Servlet 3.0 asynchronous processing mechanism
* [TorqueBox](https://github.com/torquebox/torquebox) - Ruby Web & Application Server built on JBoss and JRuby. 
  TorqueBox goes beyond providing web-centric services (supporting Rails, Rack, Sinatra, etc), to also expose other 
  enterprise-grade services to Ruby applications.
* [H2O](https://h2o.examp1e.net/) - an optimized HTTP/1, HTTP/2 server. H2O supports Rack interface for MRuby.   
  
> Miscellaneous

* [Grack](https://github.com/schacon/grack) - GIt Smart HTTP Server Rack Implementation. This project aims to replace the builtin git-http-backend 
  CGI handler distributed with C Git with a Rack application. This reason for doing this is to allow far more webservers to be able to handle Git smart 
  http requests. Grack inspired [git_http_backend.py](https://github.com/dvdotsenko/git_http_backend.py) and 
  [Git Web Access (ASP.NET/IIS)](https://github.com/yysun/Git-Web-Access)  

## Frameworks

* [Rum](https://github.com/chneukirchen/rum) - a gRand Unified Mapper for Rack by Christian Neukirchen. Rum apps use a small DSL 
  to set up the mappings. (~120 LOC)
* [Frack-MVC](https://github.com/DonSchado/Frack-MVC) - A small example implementation of how to build a simple MVC style application from 
  scratch. Check out the commit history to see how I implemented it step-by-step. This is the example code for the slide 
  [Ruby MVC from scratch with Rack](https://speakerdeck.com/donschado/ruby-mvc-from-scratch-with-rack) 
* [Hobbit](https://github.com/patriciomacadden/hobbit) - A minimalistic microframework built on top of Rack (thanks to `Rack::Builder`).
   Hobbit is a DSL inspired by Sinatra. (~ 150 LOC)
   
    * [hobbit-contrib](https://github.com/patriciomacadden/hobbit-contrib) - Contributed Hobbit extensions. For examples:
    `Hobbit::Environment`, `Hobbit::ErrorHandling`, `Hobbit::Filter`, `Hobbit::Mote` - redner using [mote](https://github.com/soveran/mote), 
    `Hobbit::Render`, `Hobbit::Session`

* [mruby-hibari](https://github.com/kentaro/mruby-hibari) - A Web application framework for Web servers that support [mruby](https://github.com/mruby/mruby)
   and Rack-based API. `mruby-hibari` currently supports the Web servers: [ngx_mruby](http://ngx.mruby.org/)-enabled Nginx, 
   [mod_mruby](http://mod.mruby.org/)-enabled Apache and [h2o](https://h2o.examp1e.net/)
* [Cuba](https://github.com/soveran/cuba) - [Rum](https://github.com/chneukirchen/rum) based microframework for web development. 
  Integrates many templates via Tilt. Incredibly small, less than 200 lines of code
  
  * [The Guide to Cuba](http://theguidetocuba.io/) - following this small book to build a Twitter clone called Frogger (work in progress).
  
* [Nancy](https://github.com/guilleiguaran/nancy) - Minimal Ruby microframework for web development inspired in `Sinatra` and `Cuba` (~150 LOC)
* [Rambutan](https://github.com/guilleiguaran/rambutan) - Ruby web microframework with Rails-ish controllers and routes.
* [NYNY](https://github.com/alisnic/nyny) - A (ridiculously) small and powerful web framework (~ 300 LOC). NYNY uses 
  [Journey](https://github.com/rails/journey) for routing(Rail's router). A NYNY app is a Rack middleware,  it can be used inside 
  Sinatra, Rails, or any other Rack-based app
* [Eldr](https://github.com/eldr-rb/eldr) - a lightweight, simple, modular and above all, clear framework without all the magic. (~500 LOC).
  Eldr uses [Mustermann](https://github.com/rkh/mustermann) to build its Router.    
* [rack-server-pages](https://github.com/migrs/rack-server-pages) - Rack middleware and application for serving dynamic pages in very 
  simple way. There are no controllers or models, just only views like a jsp, asp and php!
* [Serve](https://github.com/jlong/serve) - A small Rack-based web server that makes it easy to serve HTML, ERB, Haml, or a variety of 
  template languages from any directory.  Serve is meant to be a lightweight version of the Views part of the Rails MVC. 
  Serve has full support for Rails-style partials and layouts.
* [RESTRack](https://github.com/stjohncj/RESTRack) - RESTRack is a Rack-based MVC framework that makes it extremely easy to 
  develop RESTful data services.
  
  * [RESTRack-Client](http://github.com/stjohncj/RESTRack-Client) - A library for interacting with RESTRack based services, 
    although it provides a convenient API to any RESTful service.
  * [RESTRack-Balancer](http://github.com/stjohncj/RESTRack-Balancer) - A library for interacting with RESTful web services 
    with automatic load balancing across a cluster.
  * [RESTRack-Splitter](http://github.com/stjohncj/RESTRack-Splitter) - A library for interacting with RESTful web services 
    with automatic distribution across multiple nodes of a cluster.  
   
* [jellyfish](https://github.com/godfat/jellyfish) - Pico web framework for building API-centric web applications (~ 250 LOC)  
* [junior](https://github.com/eddanger/junior) - An MVC Web Framework
* [Kenji](https://github.com/kballenegger/Kenji) - A lightweight backend framework for Ruby
* [cramp](https://github.com/lifo/cramp) - A fully asynchronous realtime web application framework in Ruby. It is built on top of 
  EventMachine
* [Brooklyn](https://github.com/luislavena/brooklyn) - Small web tool on top of Rack. No documentation.
* [Coset](https://github.com/chneukirchen/coset-mirror) -A framework specifically for implementing RESTful Rack applications by Christian Neukirchen.
  Coset is introduced in the paper [`Introducing Rack`](http://chneukirchen.org/talks/euruko-2007/neukirchen07introducingrack.pdf).
* [Rango](https://github.com/botanicus/rango) - An ultralightweight, ultracustomizable, ultracool web framework inspired by Django  
* [Pancake](https://github.com/hassox/pancake) - Construct Rack stacks as mixins. Almost all key aspects of web frameworks are 
  covered in Pancake as mixins to help you create your own re-usable Rack Stacks without worrying about the really low level 
  plumbing.
* [Grape](https://github.com/intridea/grape) - An opinionated micro-framework for creating REST-like APIs in Ruby.
* [Napa](https://github.com/bellycard/napa) - simple framework for building Rack based APIs using Grape, Roar and ActiveRecord.  
  It's designed to make it easy to quickly create and deploy new API services by providing generators, middlewares and a console 
   similar to what you would expect from a Rails app 
* [Crep](https://github.com/crepe/crepe) - a lightweight API framework designed to help you write clean, fast web services in Ruby. 
  With an elegant and intuitive DSL inspired by RSpec, and with a nod to Grape, Crepe makes API design simple.
* [Lotus](https://github.com/lotus)- A complete MVC web framework for Ruby.
* [Camping](https://github.com/camping/camping) - A web framework which consistently stays at less than 4kB of code
* [Espresso](https://github.com/espresso/espresso) - Scalable Web Framework aimed at Speed and Simplicity. (deprecated)
* [Halcyon](https://github.com/mtodd/halcyon) - A JSON Web Application Framework for developing lightweight applications
  interfaced via JSON-encoded HTTP requests. (deprecated)
* [Wee](https://github.com/mneumann/wee) - A light-weight, very high-level and modern web-framework that makes **W**eb **e**ngineering **e**asy  
* [Mack](https://github.com/markbates/mack) - A Ruby web application framework. It takes the best ideas from several frameworks, 
  including Rails, Merb, and Ramaze  
* [Merb](https://github.com/merb/merb) - A web development framework for fast, simple, and powerful development  
* [Ramaze](https://github.com/ramaze/ramaze) - A simple, light and modular open-source web application framework written in Ruby

  * [ramaze-book](https://github.com/Ramaze/ramaze-book) - The official book for the Ramaze web framework. No longer maintained
  
* [Sin](https://github.com/raggi/sin) - A multi-app web-app DSL derived from Sinatra, riding on rack.
* [Gin](https://github.com/jcasts/gin) - A small Ruby web framework, built on Rack, which borrows from Sinatra expressiveness, 
  and targets larger applications
* [Pakyow](https://github.com/pakyow/pakyow/) - An open-source framework for the modern web. Build web-based apps faster with 
  a view-first development process that's friendly to everyone
* [Scorched](https://github.com/Wardrop/Scorched) - Light-weight, DRY as a desert, web framework for Ruby. Simliar to Sinatra. 
  Scorched is a true evolutionary enhancement of Sinatra, with more power, focus, and less clutter.
* [Sinatra](https://github.com/sinatra/sinatra) - Classy web-development dressed in a DSL for quickly creating web applications
  in Ruby with minimal effort. Sinatra is not a framework, nor a MVC, it's a wrapper around Rack.
  
  * [sinatra-contrib](https://github.com/sinatra/sinatra-contrib) - Collection of common Sinatra extensions.
  * [sinatra-receipes](https://github.com/sinatra/sinatra-recipes) - Community contributed recipes and techniques for the Sinatra Web Framework
  * [sinatra-book](https://github.com/sinatra/sinatra-book) - A cookbook full of excellent tutorials and recipes for developing Sinatra web applications.
  * [Frameworks inspired by Sinatra on Wikipedia](https://en.wikipedia.org/w/index.php?title=Sinatra_(software)&oldid=690374847) - e.g.: 
    Ruby (Padrino, Nancy), PHP (Slim, deano), JavaScript (Express), CoffeeScript (Zappa), Python (Flask), Go (Martini, Goji), Scala (Finatra, Scaltra),
    Java (Spark), Haskell (Scotty), Bash (sh.inatra), Lua (Orbit, Mercury), Perl (Dancer)

* [padrino](https://github.com/padrino/padrino-framework) - Padrino is a full-stack ruby framework built upon Sinatra

  * [padrino-contrib](https://github.com/padrino/padrino-contrib) - Contributed plugins and utilities for Padrino Framework
  * [padrino-recipes](https://github.com/padrino/padrino-recipes) - A collection of padrino templates and plugins

* [Rails](https://github.com/rails/rails) - Ruby on Rails, is a MVC web application framework written in Ruby.

* [Volt](https://github.com/voltrb/volt) - A reactive web framework where your Ruby runs on both server and client (via [Opal](https://github.com/opal/opal)).
  A framework for building data rich web applications shockingly fast. Instead of syncing data between the client and server via 
  HTTP, Volt uses a persistent connection between the client and server. When data is updated on one client, it is updated in the 
  database and any other listening clients (with almost no setup code needed). Volt apps share MVC and routes between client and
  server. Same Ruby code runs on the client and server! (Isomorphic App Development) Volt plans to integrate RethinkDB and RubyMotion.   

## Middlewares

> Where you can find middlewares

* [Rack built-in middlewares](https://github.com/rack/rack):

    * `Rack::Builder` - implements a small DSL to iteratively construct Rack applications
    * `Rack::BodyProxy` - 
    * `Rack::Cascade` - tries a request on several apps, and returns the first response that is not 404 or 405 (or in a list of 
      configurable status codes).
    * `Rack::Chunked` - Middleware that applies chunked transfer encoding to response bodies when the response does not include 
      a Content-Length header.          
    * `Rack::CommonLogger` - for creating Apache-style logfiles.
    * `Rack::ConditionalGet` - Middleware that enables conditional GET using If-None-Match and If-Modified-Since. 
      The application should set either or both of the Last-Modified or Etag response headers according to RFC 2616
    * `Rack::Config` - modifies the environment using the block given during initialization
    * `Rack::ContentLength` - Sets the Content-Length header on responses with fixed-length bodies
    * `Rack::ContentType` - Sets the Content-Type header on responses which don't have one
    * `Rack::ETag` - Adds ETag header on all String bodies. ETags are used to validate cache.
    * `Rack::File` - serves files below the root directory given, according to the path info of the Rack request. 
      e.g. when Rack::File.new("/etc") is used, you can access 'passwd' file as http://localhost:9292/passwd
    * `Rack::Deflater` - enables compression of http responses, currently supported compression algorithms: gzip, deflate, 
      identy (no transformation)
    * `Rack::Directory` - serves entries below the root given, according to the path info of the Rack request. If a directory 
      is found, the file's contents will be presented in an html based index. If a file is found, the env will be 
      passed to the specified app.
    * `Rack::ForwardRequest` - gets caught by `Rack::Recursive` and redirects the current request to the app at url
    * `Rack::Handler` - *Handlers* connect web servers with Rack. Rack includes Handlers for Thin, WEBrick, FastCGI, CGI, SCGI 
      and LiteSpeed. Handlers usually are activated by calling `MyHandler.run(myapp)`. A second optional hash can be passed 
      to include server-specific configuration.        
    * `Rack::Head` - returns an empty body for all HEAD requests. It leaves all other requests unchanged.
    * `Rack::Lint` - validates your application and the requests and responses according to the Rack spec
    * `Rack::Lock` - locks every request inside a mutex, so that every request will effectively be executed synchronously
    * `Rack::Logger` - Sets up rack.logger to write to rack.errors stream
    * `Rack::MethodOverride` - Override HTTP verbs. Lets you use HTTP verbs such as PUT or DELETE in places where the client 
       doesn't support it. The way this works is by letting the client do an HTTP POST request and set the X-HTTP-Method-Override 
       header and set the value to the intended HTTP method (such as PATCH).
    * `Rack::Mime` - Returns String with mime type if found
    * `Rack::NullLogger` -         
    * `Rack::Recursive` - allows applications called down the chain to include data from other applications (by using 
      `rack['rack.recursive.include'][...]` or raise a `ForwardRequest` to redirect internally
    * `Rack::Reloader` - High performant source reloader
    * `Rack::Runtime` - Sets an "X-Runtime" response header, indicating the response time of the request, in seconds
    * `Rack::Sendfile` - The Sendfile middleware intercepts responses whose body is being served from a file and replaces 
      it with a server specific X-Sendfile header. The web server is then responsible for writing the file contents 
      to the client
    * `Rack::Server` - Rack Server starter, used by rackup to start a rack server and use `Rack::Builder` to construct Rack 
      applications.
    * `Rack::ShowException` - for catching unhandled exceptions and presenting them in a nice and helpful way with clickable 
      backtrace.
    * `Rack::ShowStatus` catches all empty responses and replaces them
    * `Rack::Static` - intercepts requests for static files (javascript files, images, stylesheets, etc) based on the url prefixes 
      or route mappings passed in the options, and serves them using a Rack::File object. This allows a Rack stack to 
      serve both static and dynamic content. `
    * `Rack::TempfileReaper` - Middleware tracks and cleans Tempfiles created throughout a request (i.e. Rack::Multipart) 
      Ideas/strategy based on posts by Eric Wong and Charles Oliver Nutter      
    * `Rack::URLMap` - takes a hash mapping urls or paths to apps, and dispatches accordingly. Support for HTTP/1.1 host 
      names exists if the URLs start with `http://` or `https://`. URLMap modifies the `SCRIPT_NAME` and `PATH_INFO` such that 
      the part relevant for dispatch is in the `SCRIPT_NAME`, and the rest in the `PATH_INFO`. This should be taken care of 
      when you need to reconstruct the URL in order to create links.     
    * `Rack::Utils` - contains a grab-bag of useful methods for writing web applications adopted from all kinds of Ruby libraries
    * `Rack::Multipart` - A multipart form data parser, adapted from IOWA. Usually, Rack::Request#POST takes care of calling this.
    * `Rack::Request` - which also provides query string parsing and multipart handling.
    * `Rack::Response` - for convenient generation of HTTP replies and cookie handling.   
    * `Rack::MockRequest` and `Rack::MockResponse`- for efficient and quick testing of Rack application without real HTTP round-trips.
    * `Rack::Auth::Basic` - implements HTTP Basic Authentication, as per RFC 2617
    * `Rack::Auth::Digest::MD5` implements the MD5 algorithm version of HTTP Digest Authentication, as per RFC 2617.
    * `Rack::Session::Cookie` - provides simple cookie based session management. The session is a Ruby Hash stored as base64 
      encoded marshalled data set to :key (default: rack.session)
    * `Rack::Session::Pool` - provides simple cookie based session management. Session data is stored in a hash held by @pool
    * `Rack::Session::Memcache` - provides simple cookie based session management. Session data is stored in memcached                   
    * *Note that these are not middlewares*: `Rack::BodyProxy`, `Rack::Cascade`, `Rack::File`, `Rack::ForwardRequest`, 
      `Rack::Handler`, `Rack::Mime`, `Rack::Server`, `Rack::URLMap`, `Rack::Utils`, `Rack::Multipart`, `Rack::Request`, 
      `Rack::Response`, `Rack::MockRequest` and `Rack::MockResponse`, 

* [rack-contrib](https://github.com/rack/rack-contrib) - Contributed Rack Middleware and Utilities. 
  This package includes a variety of add-on components for Rack:
  
    * `Rack::AcceptFormat` - Adds a format extension at the end of the URI when there is none, corresponding to the mime-type given in the Accept HTTP header.
    * `Rack::Access` - Limits access based on IP address
    * `Rack::Backstage` - Returns content of specified file if it exists, which makes it convenient for putting up maintenance pages.
    * `Rack::CSSHTTPRequest` - Adds CSSHTTPRequest support by encoding responses as CSS for cross-site AJAX-style data loading
    * `Rack::Callbacks` - Implements DSL for pure before/after filter like Middlewares.
    * `Rack::Config` - Shared configuration for cooperative middleware.
    * `Rack::Cookies` - Adds simple cookie jar hash to env
    * `Rack::Deflect` - Helps protect against DoS attacks.
    * `Rack::Evil` - Lets the rack application return a response to the client from any place.
    * `Rack::HostMeta` - Configures `/host-meta` using a block
    * `Rack::JSONP` - Adds JSON-P support by stripping out the callback param and padding the response with the appropriate callback format.
    * `Rack::LazyConditionalGet` - Caches a global `Last-Modified` date and updates it each time there is a request that is not `GET` or `HEAD`.
    * `Rack::LighttpdScriptNameFix` - Fixes how lighttpd sets the `SCRIPT_NAME` and `PATH_INFO` variables in certain configurations.
    * `Rack::Locale` - Detects the client locale using the Accept-Language request header and sets a `rack.locale` variable in the environment.
    * `Rack::MailExceptions` - Rescues exceptions raised from the app and sends a useful email with the exception, stacktrace, and contents of the environment.
    * `Rack::NestedParams` - parses form params with subscripts (e.g., * "`post[title]=Hello`") into a nested/recursive Hash structure (based on Rails' implementation).
    * `Rack::NotFound` - A default 404 application.
    * `Rack::PostBodyContentTypeParser` - Adds support for JSON request bodies. The Rack parameter hash is populated by deserializing the JSON data provided in the request body when the Content-Type is application/json.
    * `Rack::Printout` - Prints the environment and the response per request
    * `Rack::ProcTitle` - Displays request information in process title (`$0`) for monitoring/inspection with ps(1).
    * `Rack::Profiler` - Uses ruby-prof to measure request time.
    * `Rack::RelativeRedirect` - Transforms relative paths in redirects to absolute URLs.
    * `Rack::ResponseCache` - Caches responses to requests without query strings to Disk or a user provider Ruby object. Similar to Rails' page caching.
    * `Rack::ResponseHeaders` - Manipulates response headers object at runtime
    * `Rack::Sendfile` - Enables `X-Sendfile` support for bodies that can be served from file.
    * `Rack::Signals` - Installs signal handlers that are safely processed after a request
    * `Rack::SimpleEndpoint` - Creates simple endpoints with routing rules, similar to Sinatra actions
    * `Rack::StaticCache` - Modifies the response headers to facilitiate client and proxy caching for static files that minimizes http requests and improves overall load times for second time visitors.
    * `Rack::TimeZone` - Detects the client's timezone using JavaScript and sets a variable in Rack's environment with the offset from UTC.
    * `Rack::TryStatic` - Tries to match request to a static file

* [List of Middleware](https://github.com/rack/rack/wiki/List-of-Middleware) on Rack's Wiki. Copied here (ver 2016/03/03):

    * [JSON-P](http://github.com/rack/rack-contrib/tree/master/lib/rack/contrib/jsonp.rb)
    * [Rack::Cache](http://github.com/rtomayko/rack-cache/tree/master) is suitable as a quick drop-in component to enable HTTP caching.
    * [Rack::ESI](http://github.com/Qerub/rack-esi/tree/master) is a small (but still very useful!) subset of ESI (Edge Side Includes).
    * [CloudKit](http://getcloudkit.com) includes OpenIDFilter, OAuthFilter, and RESTful JSON storage
    * [Rack::Config](http://github.com/jcrosby/rack-config/tree/master) - Shared configuration for cooperative middleware.
    * [Rack::OpenID](http://github.com/josh/rack-openid/tree/master) provides a more HTTPish API around the ruby-openid library. 
    * [Rack::Debug](http://github.com/ddollar/rack-debug)
    * [Rack::AbstractFormat](http://github.com/mynyml/rack-abstract-format)
    * [Rack::RespondTo](http://github.com/mynyml/rack-respond_to) allows triggering different actions based on requested media type.
    * [Rack::SupportedMediaTypes](http://github.com/mynyml/rack-supported-media-types) specify an app's supported media types.
    * [Rack::AcceptMediaTypes](http://github.com/mynyml/rack-accept-media-types) determine the request's prefered media type.
    * [Rack::MultipartRelated](http://github.com/lucasfais/rack-multipart_related) parses multipart/related requests and rebuild a simple/merged parameters hash.
    * [Rack::Heartbeat](https://github.com/imajes/rack-heartbeat) Add a configurable heartbeat/health-check/ping url to your app
    * [Rack::Honeypot](http://github.com/sunlightlabs/rack-honeypot) acts as a spam trap.
    * [Rack::GoogleAnalytics](http://github.com/ambethia/rack-google_analytics/tree/master) embeds Google Analytics tracking code. 
    * [Rack::Embed](http://github.com/minad/rack-embed) embeds small images via the data-url (base64) if the browser supports it. This reduces http traffic.
    * [Warden](http://github.com/hassox/warden) General Rack Authentication Framework
    * [Rack::StaticFallback](http://github.com/dolzenko/rack-static_fallback) bounces or redirects requests to missing static files.
    * [Rack::Throttle](http://github.com/datagraph/rack-throttle) provides logic for rate-limiting incoming HTTP requests to Rack applications.
    * [Rack::LinkedData](https://github.com/ruby-rdf/rack-linkeddata) implements Linked Data content negotiation.
    * [SimpleRouter](http://github.com/mynyml/simple_router)
    * [Cylon](https://github.com/dmathieu/cylon) Disallows application indexation by search engines except in production. Rack Middleware and Rails Engine.
    * [Slogger::Rack::RequestLogger](https://github.com/leandrosilva/slogger) if you want to log on Syslog.
    * [Rack::Batik::SVG](https://github.com/crapooze/jruby-rack-batik) transcodes SVG pictures to JPEG
    * [Rack::Referrals](https://github.com/deviantech/rack-referrals) extracts referring search engine info
    * [Muster](https://github.com/claco/muster) parses some or all of the query string in varying formats into hashes. Helps adding human friendly (not rack/rails nested) query string options to APIs and such.
    * [Moneta](https://github.com/minad/moneta) adds Rack::MonetaStore (places key/value store in env, support for per-request caching), Rack::MonetaCookies (allow Moneta to be used to store cookies) and Rack::MonetaRest (expose a key/value store via HTTP/REST)
    * [RouteDowncaser](https://github.com/carstengehling/route_downcaser) makes all routing in Rails case-insensitive.
    * [Rack::CanIUse](http://github.com/louismullie/rack-caniuse) checks if user agents support the HTML/CSS technologies used by your website using the CanIUse database.
    * [Rack::Attack](https://github.com/kickstarter/rack-attack) A DSL for blocking & throttling abusive clients
    * [ChromeLogger](https://github.com/cookrn/chrome_logger) A Ruby library that implements the [Chrome Logger](http://craig.is/writing/chrome-logger) spec as Rack middleware
    * [Rack::DetectTor](https://github.com/warrenguy/rack-detect-tor) Detect Tor exit users
    * [Rack::RackTorBlock](https://github.com/Gild/rack-tor-block) Block access to a rack application from any client accessing from the Tor network
    * [Rack::Turnout](https://github.com/biola/turnout/) Easily put your Rack apps into maintenance mode
    * [Rack::CAS](https://github.com/biola/rack-cas) Simple CAS client authentication
    * [Rack::AcornCache](https://github.com/acorncache/acorn-cache) Configurable HTTP proxy caching solution

* [Rubygems](https://rubygems.org/) - Search the keywords [`rack`](https://rubygems.org/search?utf8=%E2%9C%93&query=rack) or 
  [`middleware`](https://rubygems.org/search?utf8=%E2%9C%93&query=middleware)

* [Rail's ActionController Middleware Stack](https://github.com/rails/rails/tree/master/actionpack/lib/action_dispatch/middleware)

  To see what middleware your Rails app is using, open it up in command line and run:  
  
  ```
     rake middleware
  ```
  
  You will see a big list of middleware classes that your current Rails app is using. A sample outout:
  
  ```Ruby
  use ActionDispatch::Static
  use Rack::Lock
  use #<ActiveSupport::Cache::Strategy::LocalCache::Middleware:0x007f93ff6810d8>
  use Rack::Runtime
  use Rack::MethodOverride
  use ActionDispatch::RequestId
  use Rails::Rack::Logger
  use ActionDispatch::ShowExceptions
  use ActionDispatch::DebugExceptions
  use BetterErrors::Middleware
  use ActionDispatch::RemoteIp
  use ActionDispatch::Reloader
  use ActionDispatch::Callbacks
  use ActiveRecord::ConnectionAdapters::ConnectionManagement
  use ActiveRecord::QueryCache
  use ActionDispatch::Cookies
  use ActionDispatch::Session::CookieStore
  use ActionDispatch::Flash
  use ActionDispatch::ParamsParser
  use ActionDispatch::Head
  use Rack::ConditionalGet
  use Rack::ETag
  use ActionDispatch::BestStandardsSupport
  use Warden::Manager
  run MyApplication::Application.routes
  ```
  
> Middlewares for Source Reloader

* `Rack::Reloader` from [Rack built-in middlewares](https://github.com/rack/rack) - High performant source reloader
* [Shotgun](https://github.com/rtomayko/shotgun) - An automatic reloading version of the `rackup` command that's shipped with Rack.
* [rack-unreloader](https://github.com/jeremyevans/rack-unreloader) - A rack library that reloads application files when it 
  detects changes, unloading constants defined in those files before reloading
* [guard-rack](https://github.com/dblock/guard-rack) - Restart Rack when files change  
* `ActionDispatch::Reloader` from [Rail's ActionController Middleware Stack](https://goo.gl/v8ydkH) -
  Provides prepare and cleanup callbacks, intended to assist with code reloading during development
* [rack-livereload](https://github.com/johnbintz/rack-livereload) - Bring in livereload.js into handy Rack middleware  

> Middlewares for HTTP Routing

* From [Rack built-in middlewares](https://github.com/rack/rack):

  * `Rack::URLMap` - to route to multiple applications inside the same process.
  * `Rack::Static` - intercepts requests for static files (javascript files, images, stylesheets, etc) based on the url prefixes 
    or route mappings passed in the options, and serves them using a Rack::File object. This allows a Rack stack to 
    serve both static and dynamic content. `

* [rack-no-www](https://github.com/logicaltext/rack-no-www) - This piece of simple middlweware catches requests that begin 
  with "www" and redirects them to the equivalent "non-www" address. For example, a request to "http://www.example.org" will 
  be redirected to "http://example.org".
* [rack-routing](https://github.com/iAmPlus/rack-routing) - Map URL routes to Ruby methods
* [angus-router](https://github.com/moove-it/angus-router) - A router for Rack applications.
* [rack-router](https://github.com/pjb3/rack-router) - A simple router for rack apps. Requires Ruby 1.9+. (~ 200 LOC)
* [SimpleRouter](http://github.com/mynyml/simple_router) - Small and simple standalone router, meant for use with Rack applications.
  Familiar Sinatra-like DSL for defining actions. Modular architecture.
* [http_router](https://github.com/joshbuddy/http_router) - This is an HTTP router for use in either a web framework, 
  or on it's own using Rack. 
* [sinatra-router](https://github.com/brandur/sinatra-router) - A tiny vendorable router that makes it easy to try 
  routes from a number of different modular Sinatra applications  
* [sinatra-advanced-routes](https://github.com/rkh/sinatra-advanced-routes) - Make Sinatra routes first class objects 
  (extracted from BigBand). 
* [Rack::Mount](https://github.com/jm/rack-mount) - A stackable dynamic tree based Rack router.   
* [Lotus::Router](https://github.com/lotus/router) - Rack compatible, lightweight and fast HTTP Router for Ruby and `Lotus`.
* [Pendragon](https://github.com/namusyaka/pendragon) - Provides an HTTP router for use in Rack and Padrino
* [Journey](https://github.com/rails/journey) - A router for rails. Journey is a router. It routes requests.
* [Usher](https://github.com/joshbuddy/usher) - Pure ruby general purpose router with interfaces for rails, rack, email 
  or choose your own adventure
* [Roda](https://github.com/jeremyevans/roda) - Routing Tree Web Framework Toolkit
* [Rack Reverse Proxy](https://github.com/waterlink/rack-reverse-proxy) - This is a simple reverse proxy for Rack that 
  pretty heavily rips off Rack Forwarder.  

> Middlewares for Session Management

* From [Rack built-in middlewares](https://github.com/rack/rack):

  * `Rack::Session::Abstract` - includes `Rack::Session::Abstract::ID` for implementing an id based sessioning service and
    `Rack::Session::Abstract::SessionHash` for lazily loading the session from store.
  * `Rack::Session::Cookie` - provides simple cookie based session management. The session is a Ruby Hash stored as base64 
    encoded marshalled data set to :key (default: rack.session)
  * `Rack::Session::Pool` - provides simple cookie based session management. Session data is stored in a hash held by @pool
  * `Rack::Session::Memcache` - provides simple cookie based session management. Session data is stored in memcached

* From [Rail's ActionController Middleware Stack](https://github.com/rails/rails/tree/master/actionpack/lib/action_dispatch/middleware):

  * `ActionDispatch::Session::CookieStore` - Uses the cookie based session store.
  * `ActionDispatch::Session::CacheStore` - Uses the Rails cache based session store
  * `ActionDispatch::Session::MemCacheStore` - Uses the memcached based session store.
  * `ActiveRecord::SessionStore` - Uses the database based session store.
  
* [rack-deadline](https://github.com/jeremyevans/rack-deadline) - A simple rack middleware that automatically clears sessions 
  that have been open too long (by default, 1 day)
* [rack_session_access](https://github.com/railsware/rack_session_access) - provides rack middleware for 'rack.session' 
  environment management
* [Moneta](https://github.com/minad/moneta) - Moneta provides a standard interface for interacting with various kinds of key/value stores.
   Moneta supports the well-known NoSQL and document based stores.    
   
  * `Rack::Session::Moneta` - is a Rack middleware to use Moneta for storing sessions
  * `Rack::MonetaCookies` - is a Rack middleware which uses Moneta to store cookies  
  * `ActionDispatch::Session::MonetaStore` - is a Rails middleware to use Moneta for storing sessions 
  
> Middlewares for Caching

* `Rack::ETag` from [Rack built-in middlewares](https://github.com/rack/rack) - Adds ETag header on all String bodies. ETags are used to validate cache.
* [rack-cache](https://github.com/rtomayko/rack-cache) - A quick drop-in component to enable HTTP caching for
  Rack-based applications that produce freshness (Expires, Cache-Control) and/or validation (Last-Modified, ETag) information
* [Garner](https://github.com/artsy/garner) - A set of Rack middleware and cache helpers that implement various caching strategies.  
* [rack-cache-smash](https://github.com/eliotsykes/rack-cache-smash) - Rack middleware to cache bust *every* CSS and JS asset request
* [Rack::Cachely](https://github.com/markbates/rack-cachely) - Rack Middleware for working with the CachelyApp Page Cache Service, 
  [Cachely](http://www.cachelyapp.com/)
* [Faraday Http Cache](https://github.com/plataformatec/faraday-http-cache) - A Faraday middleware that respects HTTP cache, by checking expiration and validation of the stored responses.
* [Rack::Worker](https://github.com/csquared/rack-worker) - Rack middleware that implements the Worker Pattern. It processes GET requests with a worker 
  backend and only serves them straight from a cache. While processing the request it serves empty HTTP 202 responses. Your web frontend is never 
  blocked processing the request.  
* [Moneta](https://github.com/minad/moneta) - Moneta provides a standard interface for interacting with various kinds of key/value stores.
   Moneta supports the well-known NoSQL and document based stores.    
   
  * `Rack::MonetaStore` - is a Rack middleware which places a Moneta store in the environment and enables per-request caching
  * `Rack::Cache::Moneta` - provides meta and entity stores for Rack-Cache
  * `ActiveSupport::Cache::MonetaStore` - is a Rails cache implementation which uses a Moneta store as backend
  * `Ramaze::Cache::Moneta` - is integrated into the Ramaze project and allows Ramaze to use Moneta as caching store
    
> Middlewares for Authentication

* `Rack::Auth::Basic` and `Rack::Auth::Digest` from [Rack built-in middlewares](https://github.com/rack/rack) - HTTP Basic Authentication and HTTP Digest Authentication
* [Warden](https://github.com/hassox/warden) - General Rack Authentication Framework
* [Devise](https://github.com/plataformatec/devise) - A flexible authentication solution for Rails based on Warden. A complete MVC solution based on Rails engines
* [OmniAuth](https://github.com/intridea/omniauth) - A flexible authentication system utilizing Rack middleware
* [rack-oauth2](https://github.com/nov/rack-oauth2) - OAuth 2.0 Server & Client Library. Both Bearer and MAC token type are supported.
* [Rack::OAuth2::Server](https://github.com/assaf/rack-oauth2-server) - OAuth 2.0 Authorization Server as a Rack module. Supports Sinatra and Rails. 
* [rack-openid](https://github.com/grosser/rack-openid) - Provides a more HTTPish API around the `ruby-openid` library
* [rack-jwt-token-auth](https://github.com/botanicus/rack-jwt-token-auth) - JWT-based token authentication middleware for Rack.
* [Shield](https://github.com/cyx/shield) - Authentication protocol for use in your routing and model context (~ 110 LOC)
* [Heroku Bouncer](https://github.com/heroku/heroku-bouncer) - Rack middleware (implemented in Sinatra) that requires Heroku 
  OAuth on all requests.  
* [sinatra_auth_github](https://github.com/atmos/sinatra_auth_github) - A sinatra extension that provides oauth authentication to github. See Scott Chacon's 
  [Minimal Sinatra GitHub Application](https://github.com/schacon/ghapp.sinatra.min) for a demostration.   
* [Rack::FacebookConnect](https://github.com/intridea/rack_facebook_connect) - A Rack middleware for Facebook Connect authentication.
* [Rack::Cerberus](https://github.com/mig-hub/cerberus) -  Rack middleware for form-based authentication. It works roughly like Basic HTTP authentication 
  except that you can use options in order to style the authentication page.  

> Middlwares for Asset Pipeline

* [Sprockets](https://github.com/rails/sprockets) - Sprockets is a Ruby library for compiling and serving web assets. It 
  features declarative dependency management for JavaScript and CSS assets, as well as a powerful preprocessor pipeline that 
  allows you to write assets in languages like CoffeeScript, Sass and SCSS.
* [rack-sprocketize](https://github.com/petebrowne/rack-sprocketize) - a piece of Rack Middleware which uses Sprockets to concatenate 
  javascript files and then optionally compresses them.
* [rack-pack](https://github.com/petebrowne/rack-pack) - A piece of Rack Middleware that packages and optionally compresses assets such 
  as javascripts and stylesheets into single files.
* [Rack Pipeline](https://github.com/ujifgc/rack-pipeline) - A rack middleware to serve javascript and stylesheet assets 
  for ruby web applications 
* [rack-coffee](https://github.com/mattly/rack-coffee) - Simple rack middleware for serving up `CoffeeScript` files as compiled javascript
* [rack-bundle](https://github.com/logicaltext/rack-bundle) - A Rack middleware for grouping Javascripts and stylesheets into one 
  single file (styles are grouped by media type).  
* [rack-zippy](https://github.com/eliotsykes/rack-zippy) - A Rack middleware for serving static gzipped assets precompiled by 
  the Rails (4.1 and earlier) asset pipeline into the public/assets directory.
* [Hork](https://github.com/sstephenson/hork) - Rack middleware for transparently compressing JavaScript and CSS assets with 
  the YUI Compressor    
* [Sinatra AssetPack](https://github.com/rstacruz/sinatra-assetpack) - The most convenient way to manage your assets in Sinatra
* [rack-asset-compiler](https://github.com/jbaudanza/rack-asset-compiler) - Rack middleware that provides a generic interface for 
  compiling static files, such as Sass or CoffeeScript files.
* [Rack::Cat](https://github.com/ncr/rack-cat) - A Rack middleware to concatenate your assets (static, dynamic and remote) and 
  serve javascripts and stylesheets faster.       

> Middlewares for Debugging or Profiling

* From [Rack built-in middlewares](https://github.com/rack/rack):

  * `Rack::ShowException` - for catching unhandled exceptions and
    presenting them in a nice and helpful way with clickable backtrace.
  * `Rack::ShowStatus` catches all empty responses and replaces them
    with a site explaining the error  
  * `Rack::Runtime` sets an "X-Runtime" response header, indicating the response time of the request, in seconds         
      
* From [Rail's ActionController Middleware Stack](https://github.com/rails/rails/tree/master/actionpack/lib/action_dispatch/middleware): 

  * `ActionDispatch::ShowExceptions` - Rescues any exception returned by the application and calls an exceptions app that will 
     wrap it in a format for the end user.
  * `ActionDispatch::DebugExceptions` - Responsible for logging exceptions and showing a debugging page in case the request is local.    

* [rack-webconsole](https://github.com/codegram/rack-webconsole) - Rack-based interactive console (ana Rails console) in 
  your web application's frontend. That means you can interact with your application's backend from within the browser itself!
* [rack-webconsole-pry](https://github.com/mrbrdo/rack-webconsole) - based on [`rack-webconsole`](https://github.com/codegram/rack-webconsole), 
  uses [`pry`](https://github.com/pry/pry) instead of ripl, supports colors.
* [PryRescue::Rack](https://github.com/ConradIrwin/pry-rescue) - pry-rescue is an implementation of "break on unhandled exception" 
  for Ruby.  Whenever an exception is raised, but not rescued, pry-rescue will automatically open Pry for you.
* [rack-bug](https://github.com/brynary/rack-bug) - `Rack::Bug` adds a diagnostics toolbar to Rack apps. When enabled, it injects a floating div allowing exploration 
  of logging, database queries, template rendering times, etc.
* [rack-debug](https://github.com/ddollar/rack-debug) - A middleware that provides a simple interface to `ruby-debug`. Helps debug apps running 
  in Passenger  
* [rack-insight](https://github.com/pboling/rack-insight) - `Rack::Insight` adds a diagnostics toolbar to Rack apps. When enabled, 
  it injects a floating div allowing exploration of logging, database queries, template rendering times, etc. `Rack::Insight` 
  stores debugging info over many requests, incuding AJAX requests. Forked from `rack-bug`
* [racksh](https://github.com/sickill/racksh) - Console for Rack based ruby web apps. It's like script/console in Rails (~ 100 LOC) 
  or merb -i in Merb, but for any app built on Rack. Thanks to `Rack::Test::Methods` (from `rack-test`) and Ruby REPLs (`pry` and `irb`).
* [rack-monitor](https://github.com/pka/rack-monitor) - Rack middleware for collecting run-time information for monitoring tools like Munin
* [Rack::PerftoolsProfiler](https://github.com/bhb/rack-perftools_profiler) - Middleware for profiling Rack-compatible apps using 
  [perftools.rb](http://github.com/tmm1/perftools.rb)
* [Bugsnag](https://github.com/bugsnag/bugsnag-ruby) - The Bugsnag Notifier for Ruby gives you instant notification of exceptions 
  thrown from your Rails, Sinatra, Rack or plain Ruby app
* [Better Errors](https://github.com/rstacruz/better_errors) - Better Errors replaces the standard Rails error page with a much better 
  and more useful error page. It is also usable outside of Rails in any Rack app as Rack middleware.
* [rack-mini-profiler](https://github.com/MiniProfiler/rack-mini-profiler) - Middleware that displays speed badge for every html page.
  A simple but effective mini-profiler for .NET, Ruby, Go and Node.js. Introduced in [`Railscasts #368 MiniProfiler`](http://railscasts.com/episodes/368-miniprofiler)
* [New Relic RPM Ruby Agent](https://github.com/newrelic/rpm) - New Relic is a performance management system. It provides you with deep information about 
  the performance of your Rails or Ruby application as it runs in production. When running in developer mode, the New Relic Ruby Agent acts as a Rack 
  middleware that maps /newrelic to an application for showing detailed performance metrics on a page by page basis. Installed automatically in Rails applications   
  
> Middlewares for Protection

* [rack-protection](https://github.com/sinatra/rack-protection) - This gem protects against typical web attacks. Prevented Attacks includes 
  `Cross Site Request Forgery`, `Cross Site Scripting`, `Clickjacking`, `Directory Traversal`, `Session Hijacking`, 
  `IP Spoofing`.
* [rack-attack](https://github.com/kickstarter/rack-attack) - Rack middleware for blocking & throttling abusive requests. 
  It allows whitelisting, blacklisting, throttling, and tracking based on arbitrary properties of the request.  
* [rack-block](https://github.com/udzura/rack-block) - A rack middleware for controlling accesses by search bot or not, remote ip address, etc.  
* [rack-tor-block](https://github.com/Gild/rack-tor-block) - A rack middleware to block accesses to your rails application from 
  TOR nodes. Inspired by `rack-block`
* `ActionDispatch::RemoteIp` from [Rail's ActionController Middleware Stack](https://github.com/rails/rails/tree/master/actionpack/lib/action_dispatch/middleware) - Checks for IP spoofing attacks.
* [Rack::Throttle](https://github.com/bendiken/rack-throttle) - provides logic for rate-limiting incoming HTTP requests to Rack applications.

> Middlewares for WebSocket

* [faye-websocket-ruby](https://github.com/imanel/websocket-rack) - Standards-compliant WebSocket client and server. A general-purpose WebSocket implementation extracted from 
  the [Faye](http://faye.jcoglan.com/) project
* [websocket-rack](https://github.com/imanel/websocket-rack) - Rack-based WebSocket server
* [SinatraWebsocket](https://github.com/simulacre/sinatra-websocket) - Makes it easy to upgrade any request to a websocket connection in Sinatra  

> Middlewares for SEO

* [seojs-ruby](https://github.com/seojs/seojs-ruby) - Rack middleware to integrate SEO.js to your Rails or Sinatra app.
  SEO.js makes your BackboneJS, AngularJS or EmberJS apps crawlable by Google to make them appear in search results
* [Rack SEO](https://github.com/xavriley/rack-seo) - Generate SEO friendly meta tags on the fly using Rack Middleware

> Miscellaneous Middlewares

* [rack-pygmentize](https://github.com/leejarvis/rack-pygmentize) - use the generic syntax highlighter Pygments library 
  to make your code look pretty!
* [rack-flash](https://github.com/treeder/rack-flash) - Simple flash hash implementation for Rack apps.
* [sinatra-flash](https://github.com/SFEley/sinatra-flash) - An implementation of show-'em-once 'flash' messages for the Sinatra Web 
  framework. (~ 50 LOC, note this is not a middleware.)   
* [rack-emstream](https://github.com/johnbintz/rack-emstream) - Simple middleware for streaming with EventMachine-capable servers
* [sc](https://github.com/macournoyer/sc) - If static site generators were vegies, this one would be a pickle.
* [machined](https://github.com/petebrowne/machined) - A static site generator and Rack server built using Sprockets 2.0
* [rack-jekyll](https://github.com/adaoraul/rack-jekyll) - Transform your [Jekyll](http://github.com/mojombo/jekyll) app into Rack application
* [Middleman](https://github.com/middleman/middleman) - A static site generator using all the shortcuts and tools in modern web development. You can use Rack middlewares to modify content 
  on-the-fly and intercept requests before they are processed by the server (Middleman). Middleman itslef has Rack middlewares to minify CSS and JavaScript files. 
* [Brochure](https://github.com/sstephenson/brochure) - Rack application for serving static sites with ERB templates 
  (or any of the many template languages supported by Tilt)
* [Marley](https://github.com/karmi/marley) - A minimal blog engine without admin interface written in Sinatra framework. Use Rack::Auth::Basic to provide authentication.    
* [rack-ssl](https://github.com/tobmatth/rack-ssl-enforcer) - Rack middleware to force SSL
* [rack-ssl-enforcer](https://github.com/tobmatth/rack-ssl-enforcer) - A simple Rack middleware to enforce ssl connections 
* [rack-ssl-rails](https://github.com/jstorimer/rack-ssl-rails) - A simple interface to `Rack::SSL` for Rails. Provides a railtie 
  for use with rack-ssl
* [heroku-rack-ssl-enforcer-rails](https://github.com/mallowlabs/heroku-rack-ssl-enforcer-rails) - Enforce SSL on Rails application on Heroku 
* [Firehose](https://github.com/polleverywhere/firehose) - Firehose is both a Rack application and JavaScript library that makes building 
  real-time web applications possible.
* [rack-capabilities](https://github.com/joshbuddy/rack-capabilities) - Discover just what rack can do (rather, what middleware you have installed)
* [rack-legacy](https://github.com/eric1234/rack-legacy) - Run legacy environments like CGI and PHP under any rack server.  
* [Rack::Recaptcha](https://github.com/achiu/rack-recaptcha) - Drop this Rack middleware in your web application to enable 
  CAPTCHA verification via Recaptcha API.
* [Rack::Tunnel](https://github.com/benburkert/rack-tunnel) - Automatic port forwading via SSH tunneling
* [Rack::Mux](https://github.com/benburkert/rack-mux) - Multiplex multiple rack servers to the same app.
* [Rack::UserAgent::Filter](https://github.com/bebanjo/rack-useragent) - Rack Middleware for filtering by user agent
* [Rack::RevisionInfo](https://github.com/sickill/rack-revision-info) - Rack middleware showing current git (or svn) revision number of 
  deployed application
* [Rack::Health](https://github.com/mirakui/rack-health) - A health check interface for rack applications.
* [Rack::Store](https://github.com/mirakui/rack-store) - A Rack middleware what makes the env accessible anywhere while a request   
* [Rack::Plastic](https://github.com/techiferous/rack-plastic) - Helps you changing the HTML using Nokogiri
* [Rack::ToolBar](https://github.com/pboling/rack-toolbar) - Allows you to create simple Rack Middleware that will insert HTML 
  (or whatever!) into responses at specific points
* [Rack::Gsub](https://github.com/techiferous/rack-gsub) - A Rack middleware wrapper for gsub   
* [Rack::Codehighlighter](https://github.com/wbzyl/rack-codehighlighter) - A middleware which allows for easy connecting a code highlighter of somebody's choice to an HTML page 
  containing pieces of programming code.
* [Rack::JQuery](https://github.com/yb66/rack-jquery) - jQuery CDN script tags and fallback in one neat package.
* [Rack::JQueryUI](https://github.com/yb66/rack-jquery_ui) - jQuery-UI CDN script tags and fallback in one neat package.
* [Rack::JQueryUI::Themes](https://github.com/yb66/rack-jquery_ui-themes) - jQuery-UI themes CDN script tags and fallback in one neat package.
* [Rack::Backbone](https://github.com/yb66/rack-backbone) - Backbone.js CDN script tags and fallback in one neat package.
* [Rack::Polymer](https://github.com/yb66/rack-polymer) - Polymer CDN script tags and fallback in one neat package. Polymer leverages web components, a new set of standards designed 
  to provide reusable components for the web
* [Rack::Stream](https://github.com/intridea/rack-stream) - A middleware for building multi-protocol streaming rack endpoints. It's also a simple Stream DSL.
* [Rack::StreamingProxy](https://github.com/darbyfrey/rack-streaming-proxy) - A transparent streaming proxy to be used as rack middleware. Streaming proxy for Rack, the rainbows 
   to Rack::Proxy's unicorn
* [Pusher](https://github.com/macournoyer/pusher) - A Rack middleware that implement Ajax Push aka Comet
* [Robocop](https://github.com/pjkelly/robocop) - a simple Rack middleware that inserts the X-Robots-Tag into the headers of all your responses   
   
## Helpers and Tools

* From [Rack built-in middlewares](https://github.com/rack/rack):

  * `Rack::Request` - which also provides query string parsing and multipart handling.
  * `Rack::Response` - for convenient generation of HTTP replies and cookie handling.   
  * `Rack::MockRequest` and `Rack::MockResponse`- for efficient and quick testing of Rack application without real HTTP round-trips.
  * `Rack::Builder` - implements a small DSL to iteratively construct Rack applications.
  * `Rack::Lint` - validates your application and the requests and responses according to the Rack spec.
  * `Rack::File` - for serving static files.  
  * `Rack::Directory` - serves entries below the root given, according to the path info of the Rack request. If a directory 
    is found, the file's contents will be presented in an html based index. If a file is found, the env will be 
    passed to the specified app.
  * `Rack::Cascade` - tries a request on several apps, and returns the first response that is not 404 or 405 
    (or in a list of configurable status codes). 
  * `Rack::Utils` - contains a grab-bag of useful methods for writing web applications adopted from all kinds of Ruby libraries.  

  * `rackup` - a useful tool for running Rack applications, which uses the `Rack::Builder` DSL to configure middleware and build 
    up applications easily. 

    rackup automatically figures out the environment it is run in, and runs your application as FastCGI, CGI, or WEBrick—all 
    from the same configuration.
    
    * [Rackup howto](https://github.com/rack/rack/wiki/%28tutorial%29-rackup-howto)
    
* [rack-test](https://github.com/brynary/rack-test) - A layer on top of Rack's `MockRequest` similar to Merb's `RequestHelper`. (~ 200 LOC)
* [rack-test-test](https://github.com/guilleiguaran/rack-test-rest) - an extension to rack-test that when combined with Test::Unit simplifies the 
  process of unit testing properly designed RESTful API's 
* [Lookout::Rack::Test](https://github.com/lookout/lookout-rack-test) - RSpec and Cucumber test helpers.
* [test-unit-capybara](https://github.com/test-unit/test-unit-capybara/) -  integration testing helper library for Rack applications, a Capybara 
  adapter for [test-unit](https://github.com/test-unit/test-unit) 
* [Split](https://github.com/splitrb/split) - Rack based ab testing framework designed to work with Rails, Sinatra or any other rack based app. 
  Split is heavily inspired by the Abingo and Vanity rails ab testing plugins and Resque in its use of Redis   
  
## Miscellaneous

> HTTP Clients

* [Faraday](https://github.com/lostisland/faraday) - Faraday is an HTTP client lib that provides a common interface over many 
  adapters (such as Net::HTTP) and embraces the concept of Rack middleware when processing the request/response cycle.
* [rack-client](https://github.com/halorgium/rack-client) - A HTTP client that aims to be a good Rack citizen.  
* [rack-api](https://github.com/fnando/rack-api) - Create web app APIs that respond to one or more formats using an elegant DSL
* [weary](https://github.com/mwunsch/weary) - A framework and DSL for building RESTful web service clients. Full Rack integration
* [rest-core](https://github.com/godfat/rest-core) - Modular Ruby clients interface for REST APIs. rest-core consists of composable middleware that 
  allows you to build a REST client for any REST API. Or in the case of common APIs such as Facebook, Github, and Twitter, you can simply 
  use the dedicated clients provided by [rest-more](https://github.com/godfat/rest-more). See the slide 
  [The Promise of rest-core](http://godfat.org/slide/2015-01-13-rest-core-promise/) for more info.

> Vagrant Middlewares
  
* [Videos: Rack Middleware as a General Purpose Abstraction by Mitchell Hashimoto](https://www.youtube.com/watch?v=i6pyhq3ZvyI)
  * the slide is available on [speakdeck](https://speakerdeck.com/mitchellh/middleware-a-general-purpose-abstraction).
  * [Generalized middleware implementation for Ruby by Mitchell Hashimoto](https://github.com/mitchellh/middleware) - ~ 130 LOC

* [Vagrant Middlewares](https://github.com/mitchellh/vagrant/blob/master/lib%2Fvagrant%2Faction.rb) - Vagrant calls middlewares 
  "actions" and a stack of middlewares an "action sequence." (But you may also just call them middleware and middleware stacks, 
  they’re mostly called the other names for histortical purposes)
  
  * `Vagrant::Action::Warden` - The action warden is a middleware which injects itself between every other middleware, 
    watching for exceptions which are raised and performing proper cleanup on every action by calling the recover method. 
    The warden therefore allows middlewares to not worry about exceptional events, and by providing a simple callback, can 
    clean up in any erroneous case
  * `Vagrant::Action::Builtin::BoxAdd` - This middleware will download a remote box and add it to the given box collection.
  * `Vagrant::Action::Builtin::BoxCheckOutdated` - This middleware checks if there are outdated boxes. By default, it only 
    checks locally, but if box_outdated_refresh is set, it will refresh the metadata associated with a box.
  * `Vagrant::Action::Builtin::BoxRemove` - This middleware will remove a box for a given provider.    
  * `Vagrant::Action::Builtin::BoxUpdate` - This middleware updates a specific box if there are updates available.
  * `Vagrant::Action::Builtin::Call` - This middleware class allows a sort of "conditional" run within a single middlware 
    sequence. It takes another middleware runnable, runs it with the same environment, then yields the resulting env to a 
    block, allowing that block to determine the next course of action in the middleware sequence.
  * `Vagrant::Action::Builtin::ConfigValidate` - This class validates the configuration and raises an exception if there 
    are any validation errors.
  * `Vagrant::Action::Builtin::Confirm` - This class asks the user to confirm some sort of question with a "Y/N" question. 
    The only parameter is the text to ask the user. The result is placed in `env[:result]` so that it can be used with 
    the `Call` class.
  * `Vagrant::Action::Builtin::DestroyConfirm` - This class asks the user to confirm the destruction of a machine that Vagrant manages.
  * `Vagrant::Action::Builtin::EnvSet` - This middleware class allows you to modify the environment hash in the middle of a 
    middleware sequence. The new environmental data will take affect at this stage in the middleware and will persist through.
  * `Vagrant::Action::Builtin::GracefulHalt` - This middleware class will attempt to perform a graceful shutdown of the machine
     using the guest implementation  
  * `Vagrant::Action::Builtin::HandleBox` - This built-in middleware handles the box setting by verifying the box is already 
    installed, dowloading the box if it isn't, updating the box if it is requested, etc
  * `Vagrant::Action::Builtin::HandleBoxUrl`
  * `Vagrant::Action::Builtin::HandleForwardedPortCollisions` - This middleware class will detect and handle collisions with 
    forwarded ports, whether that means raising an error or repairing them automatically.
  * `Vagrant::Action::Builtin::IsState` - This middleware is meant to be used with Call and can check if a machine is in the 
    given state ID.
  * `Vagrant::Action::Builtin::Lock` - This class creates a multi-process lock using flock. The lock is active for the 
    remainder of the middleware stack.
  * `Vagrant::Action::Builtin::Message` - This middleware simply outputs a message to the UI.
  * `Vagrant::Action::Builtin::Provision` - This class will run the configured provisioners against the machine.
  * `Vagrant::Action::Builtin::ProvisionerCleanup` - This action will run the cleanup methods on provisioners and should 
    be used as part of any Destroy action.
  * `Vagrant::Action::Builtin::SSHExec` - This class will exec into a full fledged SSH console into the remote machine. 
    This middleware assumes that the VM is running and ready for SSH, and uses the `Machine#ssh_info` method to retrieve 
    SSH information necessary to connect.
  * `Vagrant::Action::Builtin::SSHRun` - This class will run a single command on the remote machine and will mirror the 
    output to the UI. The resulting exit status of the command will exist in the `:ssh_run_exit_status` key in the environment.
  * `Vagrant::Action::Builtin::SetHostname` - This middleware sets the hostname of the guest according to the 
    "vm.hostname" configuration parameter if it is set
  * `Vagrant::Action::Builtin::SyncedFolderCleanup` - This middleware will run cleanup tasks for synced folders using the 
    appropriate synced folder plugin
  * `Vagrant::Action::Builtin::SyncedFolders` - This middleware will setup the synced folders for the machine using the 
    appropriate synced folder plugin.
  * `Vagrant::Action::Builtin::WaitForCommunicator` - This waits for the communicator to be ready for a set amount of time.                         
            
> Vagrant Middleware Stack Builder and Runner
  
* `Vagrant::Action::Builder` - Action builder which provides a nice DSL for building up a middleware sequence for Vagrant 
  actions. This code is based heavily off of Rack::Builder and ActionDispatch::MiddlewareStack in Rack and Rails, respectively.
* `Vagrant::Action::Runner` - This runner does the default expected behavior of running the middleware stacks in order, 
  then reversing the order.
* `Vagrant::Action::Hook` - This class manages hooks into existing Builder stacks, and lets you add and remove middleware 
  classes. This is the primary method by which plugins can hook into built-in middleware stacks.   

## Inspiration

* [WSGI (Python)](http://wsgi.readthedocs.org/) - The Web Server Gateway Interface (WSGI) is a specification for simple 
  and universal interface between web servers and web applications or frameworks for the Python. WSGI is a Python standard 
  described in detail in [PEP 3333](http://www.python.org/dev/peps/pep-3333)

* [Rack (Ruby)](http://rack.github.io/) - Rack provides a modular and adaptable interface for developing web applications 
  in Ruby. By wrapping HTTP requests and responses it unifies the API for web servers, web frameworks, and software in between
   (the so-called middleware) into a single method call.
   
* [Clack (Lisp)](https://github.com/fukamachi/clack/) - Clack is a web application environment for Common Lisp inspired by 
  Python's WSGI and Ruby's Rack.   
  
* [Hack (Haskell)](https://github.com/nfjinjing/hack2) - Hack2 is a port of Ruby's Rack webserver interface.
  
* [JSGI (JavaScript)](http://wiki.commonjs.org/wiki/JSGI) - JavaScript Gateway Interface, is an interface between web servers 
  and JavaScript-based web applications and frameworks. It was inspired by the Rack for Ruby and WSGI for Python and was one 
  of the inspirations of PSGI for Perl.  
  
* [PSGI (Perl)](https://metacpan.org/pod/PSGI) - Perl Web Server Gateway Interface is an interface between Web servers and 
  Perl-based Web applications and frameworks that allows writing portable applications that can be run as standalone servers 
  or using CGI, FastCGI, mod_perl, et al. It is inspired by the Web Server Gateway Interface for Python, Rack for Ruby and 
  JSGI for JavaScript.

* [WSAPI (Lua)](http://keplerproject.github.io/wsapi/) - WSAPI is an API that abstracts the web server from Lua web 
  applications. By coding against WSAPI your application can run on any of the supported servers and interfaces 
  (currently CGI, FastCGI and Xavante, on Windows and UNIX-based systems). WSAPI's main influence is Ruby's Rack 
  framework, but it was also influenced by Python's WSGI (`PEP 333`). It's not a direct clone of either of them, though, 
  and tries to follow standard Lua idioms. 
  
* [StackPHP (PHP)](http://stackphp.com/) - a PHP interface for framework-agnostic code sharing

* [OWIN (.NET)](http://owin.org/) - Open Web Interface for .NET, defines a standard interface between .NET web servers 
  and web applications. The goal of the OWIN interface is to decouple server and application, encourage the development
  of simple modules for .NET web development, and, by being an open standard, stimulate the open source ecosystem of 
  .NET web development tools. [Katana](https://katanaproject.codeplex.com/) is the implementation of OWIN components.
