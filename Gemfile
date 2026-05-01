source "https://rubygems.org"

# Local dev notes (Apple system Ruby 2.6):
# - ffi 1.17+ needs Ruby 3+; pin below keeps a 2.6-compatible ffi for `bundle install`.
# - Avoid sudo: `bundle config path vendor/bundle` then `bundle install` (gems go under vendor/bundle).
# Better long-term: `brew install ruby` and use Ruby 3.x on your PATH.
gem "ffi", "~> 1.15.5"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

gem "github-pages", group: :jekyll_plugins

# If you want to use Jekyll native, uncomment the line below.
# To upgrade, run `bundle update`.

# gem "jekyll"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'hawkins'
end
