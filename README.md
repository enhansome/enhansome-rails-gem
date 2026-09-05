# Awesome Rails Gem with stars

A collection of awesome Ruby Gems for Rails development.

The goal is to help every Rails developer to build an awesome Rails product/service.

* [Rails Gem List](#rails-gem-list)
  * [User](#user)
  * [Active Record](#active-record)
  * [Plugins](#plugins)
  * [API](#api)
  * [Email](#email)
  * [File Uploading](#file-uploading)
  * [Searching](#searching)
  * [Scheduled/Recurrence Jobs](#scheduledrecurrence-jobs)
  * [View Helper](#view-helper)
  * [Environment Variables](#environment-variables)
  * [Admin Panel](#admin-panel)
  * [Logging](#logging)
  * [Debug](#debug)
  * [Coding Style](#coding-style)
  * [Testing](#testing)
  * [Production](#production)
  * [Error Logging](#error-logging)
  * [Database](#database)

## User

### Authentication

* [Devise](https://github.com/plataformatec/devise/) ⭐ 24,357 | 🐛 235 | 🌐 Ruby | 📅 2026-06-22 - Devise is a flexible authentication solution for Rails based on Warden.
* [Clearance](https://github.com/thoughtbot/clearance) ⭐ 3,736 | 🐛 37 | 🌐 Ruby | 📅 2026-07-16 - Rails authentication with email & password.
* [Devise token auth](https://github.com/lynndylanhurley/devise_token_auth) ⭐ 3,568 | 🐛 207 | 🌐 Ruby | 📅 2026-07-31 - Token based authentication for Rails JSON APIs.
* [Knock](https://github.com/nsarno/knock) ⚠️ Archived - Seamless JWT authentication for Rails API.
* [Sorcery](https://github.com/Sorcery/sorcery) ⭐ 1,464 | 🐛 55 | 🌐 Ruby | 📅 2026-07-08 - Magical Authentication for Rails. Supports ActiveRecord, DataMapper, Mongoid and MongoMapper.

### Authorization

* [Pundit](https://github.com/elabs/pundit) ⭐ 8,521 | 🐛 13 | 🌐 Ruby | 📅 2026-08-28 - Pundit provides a set of helpers which guide you in leveraging regular Ruby classes and object oriented design patterns to build a simple, robust and scaleable authorization system.
* [cancancan](https://github.com/CanCanCommunity/cancancan) ⭐ 5,684 | 🐛 92 | 🌐 Ruby | 📅 2026-08-09 - Continuation of CanCan, the authorization Gem for Ruby on Rails.CanCan is an authorization library for Ruby on Rails which restricts what resources a given user is allowed to access. All permissions are defined in a single location (the Ability class) and not duplicated across controllers, views, and database queries.
* [rolify](https://github.com/RolifyCommunity/rolify) ⭐ 3,176 | 🐛 152 | 🌐 Ruby | 📅 2026-01-24 - Role management library with resource scoping.
* [acl9](https://github.com/be9/acl9/) ⭐ 849 | 🐛 3 | 🌐 Ruby | 📅 2025-03-26 - Acl9 is a role-based authorization system that provides a concise DSL for securing your Rails application.

### Omniauth

* [omniauth-google-oauth2](https://github.com/zquestz/omniauth-google-oauth2) ⭐ 1,524 | 🐛 0 | 🌐 Ruby | 📅 2026-08-31
* [omniauth-facebook](https://github.com/mkdynamic/omniauth-facebook) ⭐ 1,267 | 🐛 2 | 🌐 Ruby | 📅 2026-08-11
* [omniauth-twitter](https://github.com/arunagw/omniauth-twitter) ⭐ 577 | 🐛 17 | 🌐 Ruby | 📅 2026-07-06
* [omniauth-github](https://github.com/intridea/omniauth-github) ⭐ 465 | 🐛 4 | 🌐 Ruby | 📅 2023-05-25
* [omniauth-weibo-oauth2](https://github.com/beenhero/omniauth-weibo-oauth2) ⭐ 134 | 🐛 0 | 🌐 Ruby | 📅 2025-07-12
* [omniauth-linkedin-oauth2](https://github.com/decioferreira/omniauth-linkedin-oauth2) ⭐ 117 | 🐛 29 | 🌐 Ruby | 📅 2024-08-09

## Active Record

* [PaperTrail](https://github.com/airblade/paper_trail) ⭐ 7,028 | 🐛 6 | 🌐 Ruby | 📅 2026-05-08 - PaperTrail lets you track changes to your models' data. It's good for auditing or versioning.
* [FriendlyId](https://github.com/norman/friendly_id) ⭐ 6,225 | 🐛 31 | 🌐 Ruby | 📅 2026-08-18 - FriendlyId is the “Swiss Army bulldozer” of slugging and permalink plugins for ActiveRecord. It allows you to create pretty URL’s and work with human-friendly strings as if they were numeric ids for ActiveRecord models.
* [AASM](https://github.com/aasm/aasm) ⭐ 5,232 | 🐛 166 | 🌐 Ruby | 📅 2026-07-05 - State machines for Ruby classes (plain Ruby, Rails Active Record, Mongoid).
* [public\_activity](https://github.com/chaps-io/public_activity) ⭐ 2,990 | 🐛 21 | 🌐 Ruby | 📅 2026-06-08 - Easy activity tracking for models - similar to Github's Public Activity.
* [paranoia](https://github.com/rubysherpas/paranoia) ⭐ 2,914 | 🐛 104 | 🌐 Ruby | 📅 2025-11-07 - ActiveRecord plugin allowing you to hide and restore records without actually deleting them.
* [globalize](https://github.com/globalize/globalize) ⭐ 2,156 | 🐛 10 | 🌐 Ruby | 📅 2026-09-02 - Rails I18n de-facto standard library for ActiveRecord model/data translation.
* [counter\_culture](https://github.com/magnusvk/counter_culture) ⭐ 2,118 | 🐛 3 | 🌐 Ruby | 📅 2026-07-08 - Turbo-charged counter caches for your Rails app. Huge improvements over the Rails standard counter caches.
* [Enumerize](https://github.com/brainspec/enumerize) ⭐ 1,761 | 🐛 13 | 🌐 Ruby | 📅 2026-08-04 - Enumerated attributes with I18n and ActiveRecord/Mongoid support. It can be integrated with Simple Form.
* [goldiloader](https://github.com/salsify/goldiloader) ⭐ 1,671 | 🐛 7 | 🌐 Ruby | 📅 2026-03-19 - Automatic ActiveRecord eager loading to reduce the number of database queries run by your application.
* [deep\_cloneable](https://github.com/moiristo/deep_cloneable) ⭐ 809 | 🐛 9 | 🌐 Ruby | 📅 2026-02-19 - This gem gives every ActiveRecord::Base object the possibility to do a deep clone that includes user specified associations.
* [Sequenced](https://github.com/djreimer/sequenced) ⭐ 407 | 🐛 6 | 🌐 Ruby | 📅 2022-11-02 - Sequenced is a simple gem that generates scoped sequential IDs for ActiveRecord models.
* [ActionStore](https://github.com/rails-engine/action-store) ⭐ 407 | 🐛 3 | 🌐 Ruby | 📅 2024-09-27 - Store different kind of actions (Like, Follow, Star, Block ...) in one table via ActiveRecord Polymorphic Association.
* [social\_shares](https://github.com/Timrael/social_shares) ⭐ 328 | 🐛 4 | 🌐 Ruby | 📅 2018-05-11 - Check how many times url was shared in social networks.
* [Validates](https://github.com/kaize/validates) ⭐ 151 | 🐛 2 | 🌐 Ruby | 📅 2017-01-13 - Validates provides collection of useful custom validators for Rails applications, including:
  * EmailValidator
  * UrlValidator
  * SlugValidator
  * MoneyValidator
  * IpValidator
  * AssociationLengthValidator
  * AbsolutePathValidator
  * UriComponentValidator
  * ColorValidator
  * EanValidator (EAN-8 & EAN-13)
* [custom\_counter\_cache](https://github.com/cedric/custom_counter_cache) ⭐ 60 | 🐛 10 | 🌐 Ruby | 📅 2026-07-30 - A simple approach to creating a custom counter cache that can be used across multiple models.
* Tagging
  * [ActsAsTaggableOn](https://github.com/mbleigh/acts-as-taggable-on) ⭐ 4,988 | 🐛 70 | 🌐 Ruby | 📅 2026-08-07 - A tagging plugin for Rails applications that allows for custom tagging along dynamic contexts.
  * [closure\_tree](https://github.com/mceachen/closure_tree) ⭐ 1,944 | 🐛 74 | 🌐 Ruby | 📅 2026-08-05 - Easily and efficiently make your ActiveRecord models support hierarchies.

## Plugins

* [Chartkick](https://github.com/ankane/chartkick) ⭐ 6,528 | 🐛 7 | 🌐 Ruby | 📅 2026-08-15 - Chartkick helps your to create beautiful Javascript charts with one line of Ruby.
* [Rails ERD](https://github.com/voormedia/rails-erd) ⭐ 4,104 | 🐛 1 | 🌐 Ruby | 📅 2026-08-27 - Generate Entity-Relationship Diagrams for Rails applications.
* [HTML::Pipeline](https://github.com/jch/html-pipeline) ⭐ 2,328 | 🐛 2 | 🌐 Ruby | 📅 2026-06-02 - GitHub HTML processing filters and utilities. This module includes a small framework for defining DOM based content filters and applying them to user provided content.
* [CKEditor](https://github.com/galetahub/ckeditor) ⭐ 2,224 | 🐛 16 | 🌐 Ruby | 📅 2025-01-23 - CKEditor is a WYSIWYG text editor designed to simplify web content creation. It brings common word processing features directly to your web pages. Enhance your website experience with our community maintained editor. [ckeditor.com](http://ckeditor.com)
* [Slack Notifier](https://github.com/stevenosloan/slack-notifier) ⭐ 1,486 | 🐛 23 | 🌐 Ruby | 📅 2023-04-24 is a simple wrapper to send notifications to [Slack](https://slack.com/) webhooks.
* [Spreadsheet](https://github.com/zdavatz/spreadsheet) ⭐ 1,150 | 🐛 13 | 🌐 Ruby | 📅 2026-04-21 - Library is designed to read and write Spreadsheet Documents.
* [Parity](https://github.com/thoughtbot/parity) ⭐ 892 | 🐛 14 | 🌐 Ruby | 📅 2025-05-23 - Shell commands for development, staging, and production parity for Heroku apps.
* [Airbrussh](https://github.com/mattbrictson/airbrussh) ⭐ 524 | 🐛 19 | 🌐 Ruby | 📅 2026-09-01 - Airbrussh pretties up your SSHKit and Capistrano output
* [kaminari](https://github.com/amatsuda/kaminari) ⭐ 26 | 🐛 0 | 🌐 Ruby | 📅 2025-01-26 - A Scope & Engine based, clean, powerful, customizable and sophisticated paginator for Rails 3 and 4.

## API

* [Grape](https://github.com/ruby-grape/grape) ⭐ 10,003 | 🐛 240 | 🌐 Ruby | 📅 2026-09-05 - Microframework to create REST-ful APIs in Ruby.
* [ActiveModel::Serializers](https://github.com/rails-api/active_model_serializers) ⭐ 5,341 | 🐛 190 | 🌐 Ruby | 📅 2025-12-08 - Serializer brings convention over configuration to your JSON generation.
* [rest-client](https://github.com/rest-client/rest-client) ⭐ 5,212 | 🐛 140 | 🌐 Ruby | 📅 2024-05-19 - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
* [Jbuilder](https://github.com/rails/jbuilder) ⭐ 4,421 | 🐛 48 | 🌐 Ruby | 📅 2026-06-01 - Jbuilder gives you a simple DSL for declaring JSON structures that beats massaging giant hash structures. This is particularly helpful when the generation process is fraught with conditionals and loops.
* [has\_scope](https://github.com/plataformatec/has_scope) ⭐ 1,727 | 🐛 3 | 🌐 Ruby | 📅 2026-03-27 - Map incoming controller parameters to named scopes in your resources.
* Documentation
  * [Grape Swagger UI](https://github.com/swagger-api/swagger-ui) ⭐ 29,000 | 🐛 1,127 | 🌐 JavaScript | 📅 2026-09-04 - Display documentation that is generated using Grape Swagger.
  * [Grape Swagger](https://github.com/ruby-grape/grape-swagger) ⭐ 1,099 | 🐛 132 | 🌐 Ruby | 📅 2026-09-02 - Autogenerate documentation on Grape API.
  * [apiary](https://apiary.io/) - Work together to quickly design, prototype, document and test APIs.
  * [apiblueprint](https://apiblueprint.org) - API Documentation with powerful tooling.

## Email

* [letter\_opener](https://github.com/ryanb/letter_opener) ⭐ 3,841 | 🐛 2 | 🌐 Ruby | 📅 2026-04-25 - Preview mail in the browser instead of sending.

## File Uploading

* [Paperclip](https://github.com/thoughtbot/paperclip) ⚠️ Archived - Easy file attachment management for ActiveRecord.
* [Carrierwave](https://github.com/carrierwaveuploader/carrierwave) ⭐ 8,775 | 🐛 47 | 🌐 Ruby | 📅 2026-09-05 - Carrierwave is a classier solution for file uploads for Rails, Sinatra and other Ruby web frameworks.
  * [carrierwave\_backgrounder](https://github.com/lardawge/carrierwave_backgrounder) ⚠️ Archived - Offload CarrierWave's image processing and storage to a background process using Delayed Job, Resque, Sidekiq, Qu, Queue Classic or Girl Friday.
  * [CarrierWave ImageOptimizer](https://github.com/jtescher/carrierwave-imageoptimizer) ⭐ 210 | 🐛 4 | 🌐 Ruby | 📅 2022-03-08 - This gem allows you to simply optimize CarrierWave images via jpegoptim or optipng using the image\_optimizer gem.
  * [CarrierWave Crop](https://github.com/kirtithorat/carrierwave-crop/) ⭐ 93 | 🐛 16 | 🌐 Ruby | 📅 2015-09-08 - Carrierwave extension to crop uploaded images using Jcrop plugin with preview.
* [fog](https://github.com/fog/fog) ⭐ 4,297 | 🐛 9 | 🌐 Ruby | 📅 2024-11-19 - Fog is the Ruby cloud services library, top to bottom.
* [shrine](https://github.com/janko-m/shrine) ⭐ 3,285 | 🐛 0 | 🌐 Ruby | 📅 2026-08-28 -File Attachment toolkit for Ruby applications
* [MiniMagick](https://github.com/minimagick/minimagick) ⭐ 2,864 | 🐛 1 | 🌐 Ruby | 📅 2026-08-31 - MiniMagick is a ruby wrapper for ImageMagick or GraphicsMagick command line.
* [refile](https://github.com/refile/refile) ⭐ 2,433 | 🐛 26 | 🌐 Ruby | 📅 2024-07-01 - Refile is a modern file upload library for Ruby applications. It is simple, yet powerful.
* [remotipart](https://github.com/JangoSteve/remotipart) ⭐ 997 | 🐛 42 | 🌐 Ruby | 📅 2021-03-23 - Rails jQuery file uploads via standard Rails "remote: true" forms.
* [Dragonfly](http://markevans.github.io/dragonfly) - Dragonfly is for on-the-fly file processing - suitable for images or other attachments

## Searching

* [searchkick](https://github.com/ankane/searchkick) ⭐ 6,720 | 🐛 9 | 🌐 Ruby | 📅 2026-08-17 - Intelligent search made easy with Rails and Elasticsearch.
* [ransack](https://github.com/activerecord-hackery/ransack) ⭐ 5,860 | 🐛 156 | 🌐 Ruby | 📅 2026-05-31 - Ransack enables the creation of both simple and advanced search forms for your Ruby on Rails application.
* [elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) ⭐ 3,083 | 🐛 53 | 🌐 Ruby | 📅 2025-10-08 - Elasticsearch integrations for ActiveModel/Record and Ruby on Rails.
* [sunspot](https://github.com/sunspot/sunspot) ⭐ 2,978 | 🐛 152 | 🌐 JavaScript | 📅 2026-08-18 - Sunspot is a Ruby library for expressive, powerful interaction with the Solr search engine. Sunspot is built on top of the RSolr library, which provides a low-level interface for Solr interaction; Sunspot provides a simple, intuitive, expressive DSL backed by powerful features for indexing objects and searching for them.
* [Chewy](https://github.com/toptal/chewy) ⭐ 1,899 | 🐛 5 | 🌐 Ruby | 📅 2026-09-02 - High-level Elasticsearch Ruby framework based on the official elasticsearch-ruby client.
* [pg\_search](https://github.com/Casecommons/pg_search) ⭐ 1,579 | 🐛 155 | 🌐 Ruby | 📅 2026-08-10 - pg\_search builds ActiveRecord named scopes that take advantage of PostgreSQL's full text search

## Scheduled/Recurrence Jobs

* [Sidekiq](https://github.com/mperham/sidekiq) ⭐ 13,554 | 🐛 22 | 🌐 Ruby | 📅 2026-09-03 - Simple, efficient background processing for Ruby.
  * [sidekiq-cron](https://github.com/ondrejbartas/sidekiq-cron) ⭐ 1,943 | 🐛 3 | 🌐 Ruby | 📅 2026-05-27 - Scheduler / Cron for Sidekiq jobs
  * [sidetiq](https://github.com/tobiassvn/sidetiq) - Recurring jobs for sidekiq.
  * [sidekiq-scheduler](https://github.com/Moove-it/sidekiq-scheduler) - Lightweight job scheduler extension for Sidekiq
* [Resque](https://github.com/resque/resque) ⭐ 9,476 | 🐛 82 | 🌐 Ruby | 📅 2026-08-31 - Redis-backed Ruby library for creating background jobs, placing them on multiple queues, and processing them later.
* [Whenever](https://github.com/javan/whenever) ⭐ 8,857 | 🐛 84 | 🌐 Ruby | 📅 2026-07-01 - Whenever is a Ruby gem that provides a clear syntax for writing and deploying cron jobs.
* [Delayed Job](https://github.com/collectiveidea/delayed_job) ⭐ 4,824 | 🐛 143 | 🌐 Ruby | 📅 2026-07-13 - Database based asynchronous priority queue system.
* [Sucker Punch](https://github.com/brandonhilkert/sucker_punch) ⭐ 2,630 | 🐛 2 | 🌐 Ruby | 📅 2025-12-24 - Sucker punch is a single-process Ruby asynchronous processing library.
* [Rufus-Scheduler](https://github.com/jmettraux/rufus-scheduler) ⭐ 2,446 | 🐛 12 | 🌐 Ruby | 📅 2026-06-22 - Rufus-scheduler is a Ruby gem for scheduling pieces of code (jobs). It understands running a job AT a certain time, IN a certain time, EVERY x time or simply via a CRON statement.

## View Helper

* [Simple Form](https://github.com/plataformatec/simple_form) ⭐ 8,229 | 🐛 37 | 🌐 Ruby | 📅 2026-04-01 - Simple form aims to be as flexible as possible while helping you with powerful components to create your forms. The basic goal of Simple Form is to not touch your way of defining the layout, letting you find the better design for your eyes.
* [formtastic](https://github.com/justinfrench/formtastic) ⭐ 5,213 | 🐛 6 | 🌐 Ruby | 📅 2026-02-28 - Formtastic is a Rails FormBuilder DSL (with some other goodies) to make it far easier to create beautiful, semantically rich, syntactically awesome, readily stylable and wonderfully accessible HTML forms in your Rails applications
* [cocoon](https://github.com/nathanvda/cocoon) ⭐ 3,072 | 🐛 34 | 🌐 Ruby | 📅 2023-08-08 - Dynamic nested forms using jQuery made easy
* [cells](https://github.com/apotonick/cells) ⭐ 3,070 | 🐛 38 | 🌐 Ruby | 📅 2024-12-02 - Cells allow you to encapsulate parts of your UI into components into view models. View models, or cells, are simple ruby classes that can render templates.
* [meta-tags](https://github.com/kpumuk/meta-tags) ⭐ 2,801 | 🐛 11 | 🌐 Ruby | 📅 2026-09-01 - Search Engine Optimization (SEO) plugin for Ruby on Rails applications.
* [Nested Form](https://github.com/ryanb/nested_form) ⚠️ Archived - This is a Rails gem for conveniently manage multiple nested models in a single form. It does so in an unobtrusive way through jQuery or Prototype. It can also be integrated with Simple Form.
* [active\_link\_to](https://github.com/comfy/active_link_to) ⭐ 853 | 🐛 10 | 🌐 Ruby | 📅 2024-04-07 - active\_link\_to adds css 'active' class to your links.
* [i18n Country Code Select](https://github.com/onomojo/i18n_country_select) ⭐ 27 | 🐛 6 | 🌐 Ruby | 📅 2022-02-14 - I18n Country Code Select Form Helper for Rails 3 & 4.
* [Subdivision Select](https://github.com/cllns/subdivision_select) ⭐ 20 | 🐛 4 | 🌐 Ruby | 📅 2024-01-22 - A Rails plugin to populate a state/province select box from country\_select.

## Environment Variables

* [dotenv](https://github.com/bkeepers/dotenv) ⭐ 6,764 | 🐛 18 | 🌐 Ruby | 📅 2026-06-22 - Dotenv is a gem that allows you to set your environment variables in .env file, and it will load it in to ENV.
* [Figaro](https://github.com/laserlemon/figaro) ⭐ 3,745 | 🐛 60 | 🌐 Ruby | 📅 2025-06-29 - Figaro is very simple, Heroku-friendly Rails app configuration using ENV and a single YAML file.
* [Config](https://github.com/railsconfig/config) ⭐ 2,170 | 🐛 25 | 🌐 Ruby | 📅 2026-07-28 - Multi-environment YAML style configurations that helps easily manage environment specific settings in an easy and usable manner.
* [opsworks-dotenv](https://github.com/mikamai/opsworks-dotenv) ⭐ 8 | 🐛 1 | 🌐 Ruby | 📅 2016-02-06 - Opsworks-dotenv let you configure the environment for you Rails application using OpsWorks, Chef and Dotenv.

## Admin Panel

* [RailsAdmin](https://github.com/sferik/rails_admin) ⭐ 7,957 | 🐛 202 | 🌐 Ruby | 📅 2026-09-05 - RailsAdmin is a Rails engine that provides an easy-to-use interface for managing your data.
* [administrate](https://github.com/thoughtbot/administrate) ⭐ 6,031 | 🐛 134 | 🌐 JavaScript | 📅 2026-08-26 - A Rails engine that helps you put together a super-flexible admin dashboard.
* [Trestle](https://github.com/TrestleAdmin/trestle) ⭐ 1,990 | 🐛 122 | 🌐 Ruby | 📅 2025-09-25 - A modern, responsive admin framework for Ruby on Rails
* [ActiveAdmin](http://activeadmin.info) - ActiveAdmin is a administration framework for Ruby on Rails applications.
  * [active\_skin](https://github.com/rstgroup/active_skin) ⭐ 423 | 🐛 17 | 🌐 Sass | 📅 2023-01-20: Flat skin for active admin.
* [Typus](https://github.com/typus/typus) - Typus is a control panel for Ruby on Rails applications to allow trusted users edit structured content.

## Logging

* [Ahoy](https://github.com/ankane/ahoy) ⭐ 4,479 | 🐛 6 | 🌐 Ruby | 📅 2026-08-17 - Ahoy provides a solid foundation to track visits and events in Ruby, JavaScript, and native apps.
* [Lograge](https://github.com/roidrage/lograge) ⭐ 3,571 | 🐛 69 | 🌐 Ruby | 📅 2026-07-08 - An attempt to tame Rails' default policy to log everything.
* [Impressionist](https://github.com/charlotte-ruby/impressionist) ⭐ 1,527 | 🐛 81 | 🌐 Ruby | 📅 2026-02-08 - Impressionist can log page impressions (technically action impressions), but it is not limited to that. You can log impressions multiple times per request. And you can also attach it to a model. The goal of this project is to provide customizable stats that are immediately accessible in your application as opposed to using Google Analytics and pulling data using their API.

## Debug

* [terminal-notifier](https://github.com/julienXX/terminal-notifier) ⭐ 7,307 | 🐛 8 | 🌐 Objective-C | 📅 2026-08-30 - terminal-notifier is a command-line tool to send Mac OS X User Notifications, which are available in Mac OS X 10.8 and higher.
* [Better Errors](https://github.com/charliesome/better_errors) ⭐ 6,861 | 🐛 68 | 🌐 Ruby | 📅 2024-07-09 - Better errors replaces the standard Rails error page with a much better and more useful error page.
  * If you would like to use Better Errors' advanced features (REPL, local/instance variable inspection, pretty stack frame names), you need to add the [binding\_ \_of\_\_caller](https://github.com/banister/binding_of_caller) ⭐ 672 | 🐛 3 | 🌐 Ruby | 📅 2026-02-15.
* [awesome\_print](https://github.com/awesome-print/awesome_print) ⭐ 4,077 | 🐛 110 | 🌐 Ruby | 📅 2024-08-15 - Awesome Print is a Ruby library that pretty prints Ruby objects in full color exposing their internal structure with proper indentation.
* [RailsPanel](https://github.com/dejan/rails_panel) ⭐ 3,868 | 🐛 26 | 🌐 JavaScript | 📅 2026-05-27 - RailsPanel is a Chrome extension for Rails development that will end your tailing of development.log.
* [letter\_opener](https://github.com/ryanb/letter_opener) ⭐ 3,841 | 🐛 2 | 🌐 Ruby | 📅 2026-04-25 - Preview email in the default browser instead of sending it. This means you do not need to set up email delivery in your development environment, and you no longer need to worry about accidentally sending a test email to someone else's address.
* [byebug](https://github.com/deivid-rodriguez/byebug) ⭐ 3,350 | 🐛 101 | 🌐 Ruby | 📅 2026-07-27 - Byebug is a simple to use, feature rich debugger for Ruby 2. It uses the new TracePoint API for execution control and the new Debug Inspector API for call stack navigation, so it doesn't depend on internal core sources.
  * [pry-byebug](https://github.com/deivid-rodriguez/pry-byebug) ⭐ 2,028 | 🐛 50 | 🌐 Ruby | 📅 2026-05-18 - Pry navigation commands via byebug.
* [spring](https://github.com/rails/spring) ⭐ 2,815 | 🐛 55 | 🌐 Ruby | 📅 2026-06-30 - Spring is a Rails application preloader. It speeds up development by keeping your application running in the background so you don't need to boot it every time you run a test, rake task or migration.
* [rails-footnotes](https://github.com/josevalim/rails-footnotes) ⭐ 1,521 | 🐛 17 | 🌐 Ruby | 📅 2026-09-03 - Rails footnotes displays footnotes in your application for easy debugging, such as sessions, request parameters, cookies, filter chain, routes, queries, etc.
* [web-console](https://github.com/rails/web-console) ⭐ 1,437 | 🐛 14 | 🌐 Ruby | 📅 2026-02-23 - Web Console is a debugging tool for your Ruby on Rails applications.
* [pry-rails](https://github.com/rweng/pry-rails) ⭐ 1,361 | 🐛 33 | 🌐 Ruby | 📅 2024-06-20 - Avoid repeating yourself, use pry-rails instead of copying the initializer to every rails project. This is a small gem which causes rails console to open pry. It therefore depends on pry.
* [g](https://github.com/jugyo/g) ⭐ 117 | 🐛 17 | 🌐 Ruby | 📅 2013-07-31 - The Kernel.g that works like Kernel.p by using terminal-notifier or growl.

## Coding Style

* [RuboCop](https://github.com/bbatsov/rubocop) ⭐ 12,893 | 🐛 149 | 🌐 Ruby | 📅 2026-09-04 - Rubocop is a Ruby static code analyzer. Out of the box it will enforce many of the guidelines outlined in the community [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide) ⭐ 16,546 | 🐛 73 | 📅 2026-07-20.
* [Pronto](https://github.com/mmozuras/pronto) ⭐ 2,670 | 🐛 15 | 🌐 Ruby | 📅 2026-08-30 - Quick automated code review of your changes
* [Metric Fu](https://github.com/metricfu/metric_fu) ⭐ 627 | 🐛 31 | 🌐 Ruby | 📅 2024-02-27 - A fist full of code metrics
* [Rails Best Practice](https://github.com/railsbp/rails_best_practices) - Rails best practice is a code metric tool to check the quality of rails codes.

## Testing

* [Capybara](https://github.com/jnicklas/capybara) ⭐ 10,174 | 🐛 22 | 🌐 Ruby | 📅 2026-07-13 - Capybara helps you test web applications by simulating how a real user would interact with your app. And drivers:
  * [poltergeist](https://github.com/teampoltergeist/poltergeist) ⚠️ Archived - Poltergeist allows you to run your Capybara tests on a headless WebKit browser, provided by PhantomJS.
  * [capybara-webkit](https://github.com/thoughtbot/capybara-webkit) ⚠️ Archived - Capybara-webkit is a capybara driver that uses Webkit via QtWebkit.
  * [page-object](https://github.com/cheezy/page-object) ⭐ 648 | 🐛 28 | 🌐 Ruby | 📅 2021-05-03 - Page-object is a simple gem that assists in creating flexible page objects for testing browser based applications.
  * [selenium-webdriver](https://github.com/vertis/selenium-webdriver) ⭐ 25 | 🐛 3 | 🌐 Ruby | 📅 2015-12-17 - Selenium-webdriver provides ruby bindings for WebDriver.
* [factory\_bot](https://github.com/thoughtbot/factory_bot) ⭐ 8,169 | 🐛 79 | 🌐 Ruby | 📅 2026-08-21 - Factory\_bot is a fixtures replacement with a straightforward definition syntax, support for multiple build strategies (saved instances, unsaved instances, attribute hashes, and stubbed objects), and support for multiple factories for the same class (user, admin\_user, and so on), including factory inheritance.
* [VCR](https://github.com/vcr/vcr) ⭐ 6,073 | 🐛 87 | 🌐 Ruby | 📅 2026-06-23 - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests.
* [rspec-rails](https://github.com/rspec/rspec-rails) ⭐ 5,274 | 🐛 64 | 🌐 Ruby | 📅 2026-09-03 - Rspec-rails is a testing framework for Rails 3.x and 4.x.
* [SimpleCov](https://github.com/colszowka/simplecov) ⭐ 4,919 | 🐛 1 | 🌐 Ruby | 📅 2026-09-04 - SimpleCov is a code coverage analysis tool for Ruby.
* [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) ⭐ 3,581 | 🐛 42 | 🌐 Ruby | 📅 2026-08-10 - Shoulda-matchers provides serveral matchers for testing common Rails functionality.
* [Timecop](https://github.com/travisjeffery/timecop) ⭐ 3,424 | 🐛 11 | 🌐 Ruby | 📅 2026-04-12 - A gem providing "time travel" and "time freezing" capabilities, making it dead simple to test time-dependent code.
* [factory\_bot\_rails](https://github.com/thoughtbot/factory_bot_rails) ⭐ 3,138 | 🐛 8 | 🌐 Ruby | 📅 2026-07-21 - Factory\_bot\_rails provides Rails integration for factory\_bot.
* [Database Cleaner](https://github.com/DatabaseCleaner/database_cleaner) ⭐ 2,965 | 🐛 31 | 🌐 Ruby | 📅 2026-06-01 - Database Cleaner is a set of strategies for cleaning your database in Ruby.Support ActiveRecord, DataMapper, Sequel, MongoMapper, Mongoid, CouchPotato, Ohm and Redis.
* [ResponseCodeMatchers](https://github.com/r7kamura/response_code_matchers) ⭐ 61 | 🐛 0 | 🌐 Ruby | 📅 2017-06-05 - ResponseCodeMatchers provides rspec matchers to match http response code.
* [factory\_factory\_girl](https://github.com/st0012/factory_factory_girl) ⭐ 45 | 🐛 0 | 🌐 Ruby | 📅 2015-08-25 - FactoryFactoryGirl lets you generate factory files more efficiently with naming rules.

### Security

* [brakeman](https://github.com/presidentbeef/brakeman) ⭐ 7,268 | 🐛 117 | 🌐 Ruby | 📅 2026-08-13 - Brakeman is a static analysis tool which checks Ruby on Rails applications for security vulnerabilities.
* [Secure Headers](https://github.com/twitter/secureheaders) ⭐ 3,226 | 🐛 13 | 🌐 Ruby | 📅 2026-07-27 -  Secure Headers will automatically apply several headers that are related to security.
* [bundle-audit](https://github.com/rubysec/bundler-audit) ⭐ 2,757 | 🐛 48 | 🌐 Ruby | 📅 2026-09-04 - bundler-audit is a patch-level verification tool for Bundler which checks for vulnerable versions of gems and insecure gem sources.

## Production

* [Capistrano](https://github.com/capistrano/capistrano) ⭐ 12,992 | 🐛 74 | 🌐 Ruby | 📅 2026-07-19 - Remote multi-server automation tool.
* [Rack Attack](https://github.com/kickstarter/rack-attack) ⭐ 5,760 | 🐛 19 | 🌐 Ruby | 📅 2026-07-02 - Rack middleware to blocking & throttling.
* [Mina](https://github.com/mina-deploy/mina) ⭐ 4,352 | 🐛 35 | 🌐 Ruby | 📅 2024-08-01 - fast deployer and server automation tool.
* [production\_rails](https://github.com/ankane/production_rails) ⭐ 2,320 | 🐛 0 | 📅 2026-03-31 - Best practices for running Rails in production.
* [Responders](https://github.com/plataformatec/responders) ⭐ 2,058 | 🐛 11 | 🌐 Ruby | 📅 2026-08-27 - A set of Rails responders to dry up your application.
* [Slowpoke](https://github.com/ankane/slowpoke) ⭐ 395 | 🐛 0 | 🌐 Ruby | 📅 2026-04-04 - Rack::Timeout is great. Slowpoke makes it better.

## Error Logging

* [Errbit](https://github.com/errbit/errbit) ⭐ 4,270 | 🐛 137 | 🌐 Ruby | 📅 2026-09-04 - Open source notifier gem compliant with Airbrake.
* [Airbrake](https://github.com/airbrake/airbrake) ⭐ 984 | 🐛 20 | 🌐 Ruby | 📅 2024-12-21 - Notifier gem for integrating apps with Airbrake
* [Rollbar](https://github.com/rollbar/rollbar-gem) ⭐ 484 | 🐛 45 | 🌐 Ruby | 📅 2026-05-06 - Exception tracking and logging from Ruby to Rollbar.

## Database

* [rails\_db](https://github.com/igorkasyanchuk/rails_db) ⭐ 1,495 | 🐛 8 | 🌐 JavaScript | 📅 2026-06-19 - Rails Database Viewer and SQL Query Runner

## Asset Pipeline

* [Alaska](https://github.com/mavenlink/alaska) ⚠️ Archived - ExecJS runtime with persistent connection to nodejs, speeds up your coffeescript compilation process during development and deployment.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-05._
