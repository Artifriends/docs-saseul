# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 3.9.2"
gem "kramdown-parser-gfm", "~> 1.1.0"
gem "webrick", "~> 1.7"

group :jekyll_plugins do
  gem 'jekyll-paginate'
  gem 'jekyll-redirect-from'
  gem 'jekyll-seo-tag'
  gem 'jekyll-archives'
  gem 'jekyll-sitemap'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

group :test do
  gem "html-proofer", "~> 3.18"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?