source 'https://rubygems.org'

gem 'jekyll'

group :jekyll_plugins do
   gem 'jekyll-feed'
end

# Add github pages support 
source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
