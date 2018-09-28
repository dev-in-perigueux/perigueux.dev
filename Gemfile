# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 3.8.4"
gem 'jekyll-athena', :git => 'https://github.com/borisschapira/athena', :branch => 'master'

gem 'rake'

group :jekyll_tests do
  gem 'ffi', '~> 1.9', '>= 1.9.18'
  gem 'html-proofer'
end

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem 'jekyll-sitemap'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# Added at 2018-09-28 22:58:07 +0200 by boris:
gem "jekyll-microtypo", "~> 0.2.3"
