WBlog
=======
[![Build Status](https://travis-ci.org/windy/wblog.svg?branch=master)](https://travis-ci.org/windy/wblog)
[![Maintainability](https://api.codeclimate.com/v1/badges/545d8372a9dda70b77fe/maintainability)](https://codeclimate.com/github/windy/wblog/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/545d8372a9dda70b77fe/test_coverage)](https://codeclimate.com/github/windy/wblog/test_coverage)

The open source Ruby on Rails blog system built for mobile. WBlog is licensed under MIT, free to use.

Now fully supports Ruby on Rails 6.1 version!!!

New: Now upgraded from webpacker to jsbundling & cssbundling.

* Extremely user-friendly reading experience
* Clean built-in comment system
* Simple yet powerful blog publishing process

Visit my blog to experience: <https://yafeilee.com>

Screenshots below: <#screenshots>

### WBlog Design Goals

* Mobile user experience first
* Independent and clean comment system
* Great blog syntax highlighting support
* Email subscription
* Markdown support
* Maximum independence

### Features

* Mobile access priority
* Responsive design, supports all screen terminals, and supports WeChat QR code for continued reading and sharing
* Built-in comment system, clean and convenient
* Markdown support, blog syntax highlighting, convenient for technical blogs
* Open source and commercial use, strong customization capability

### Goal

The best independent blog building system under `Ruby on Rails`

### Development Environment

WBlog is a standard Ruby on Rails application. Development environment depends on:

* Ruby ( = 3.1.2 )
* Postgresql ( >= 9.x )
* node ( >= 18 )

Configure WBlog:

  ```shell
  # rails dependencies
  gem install bundler
  bundle install
  # node dependencies
  npm install yarn -g
  yarn install
  # configuration updates
  cp config/application.yml.example config/application.yml
  cp config/database.yml.example config/database.yml
  ```

  Update corresponding configurations: application.yml & database.yml.

That's it, you can try to start it:

  ```shell
  bin/dev
  ```

Login to http://localhost:3000/admin to publish your first blog.

### Deployment

WBlog uses `mina` as an automated deployment tool, using `nginx`, `puma` as related containers.

The deployment process is at: [WBlog Deployment Process](https://github.com/windy/wblog/wiki)

### Technology Stack

* Ruby on Rails 6.1
* Ruby 3.1.2
* Bootstrap 4
* mina
* slim
* Postgresql


## Recommended Ruby Open Source Blogs

* writings.io( Ruby on Rails 4.0.2 ): <https://github.com/chloerei/writings>
* jekyll( Ruby Gem, Markdown, Static ): <http://jekyllrb.com/>
* octopress( Github Pages ): <http://octopress.org/>
* middleman( Ruby Gem, Static ): <https://github.com/middleman/middleman>
* robbin_site( Padrino ): <https://github.com/robbin/robbin_site>

### Screenshots

Home Page:

![screenshot home](https://github.com/windy/wblog/raw/master/doc/wblog_s_en/home.png)

Mobile Home Page:

![screenshot home small](https://github.com/windy/wblog/raw/master/doc/wblog_s_en/home-small.png)

Expanded Mobile Home Page:

![screenshot home hover](https://github.com/windy/wblog/raw/master/doc/wblog_s_en/home-small-hover.png)

Blog Detail Page:

![screenshot post](https://github.com/windy/wblog/raw/master/doc/wblog_s_en/post.png)

Expanded Blog Detail Page:

![screenshot post hover](https://github.com/windy/wblog/raw/master/doc/wblog_s_en/post-hover.png)

Admin Login Page:

![screenshot admin](https://github.com/windy/wblog/raw/master/doc/wblog_s_en/admin-login.png)

Admin Dashboard:

![screenshot admin](https://github.com/windy/wblog/raw/master/doc/wblog_s_en/admin-dashboard.png)

Publish New Blog Page:

![screenshot admin](https://github.com/windy/wblog/raw/master/doc/wblog_s_en/admin-post.png)

Blog Management Page:

![screenshot admin](https://github.com/windy/wblog/raw/master/doc/wblog_s_en/admin-posts.png)