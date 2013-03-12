redmine-redcase
===============

Redmine Redcase is a Plugin for managing test cases.

Steps to install: 


Clone:
```
$ cd redmine_path && git clone git@github.com:sadfuzzy/redmine-redcase.git plugins/redcase
```

Add gem to your Gemfile:
```
$ echo "gem 'prototype-rails'" >> Gemfile 
```

Run bundle:
```
$ bundle install
```

Run migrations:
```
$ bundle exec rake redmine:plugins 
```

In Redmine enable TestCase tracker and you'll get a 'Test case' tab in projects' menu.
