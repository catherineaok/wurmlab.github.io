source "http://rubygems.org"

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)


group :development do
  gem 'github-pages', versions['github-pages']
end
