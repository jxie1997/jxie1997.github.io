source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# NOTE: github-pages pins a very old Jekyll/Liquid that relies on Ruby APIs
# (String#tainted?) removed in Ruby 3.2+, so it can't run locally on a modern
# Ruby. GitHub's classic Pages build uses its own pinned environment on their
# servers regardless of this Gemfile (no Actions workflow here), so using a
# current Jekyll locally for previewing is safe and doesn't affect deploys.
# gem "github-pages", group: :jekyll_plugins
gem "jekyll"
gem "webrick"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-redirect-from"
  gem "jekyll-paginate"
end
