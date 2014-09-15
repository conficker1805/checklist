Checklist for your new project
=========

* Create new gemset and declare ruby version.

```sh
  touch .ruby-version
  echo ruby-[latest-version] > .ruby-version
  touch .ruby-gemset
  echo [your-gemset] > .ruby-gemset
```

* Use the latest version of Rails.
* Use the latest version of RSpec.
* Add ruby version to your Gemfile.
* Remove the `test` folder of MiniTest.
* Select the right gemset if you're using RubyMine.
* Config your database if you're using Postgres.
* Make sure there are `production` and `staging` branches.

