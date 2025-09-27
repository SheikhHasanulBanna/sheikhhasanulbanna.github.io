source 'https://rubygems.org'

group :jekyll_plugins do
  gem 'jekyll'
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-redirect-from'
  gem 'jemoji'
  gem 'webrick', '~> 1.8'
end

# GitHub Pages gem (pulls correct versions of Jekyll + plugins)
gem 'github-pages'

# Required for caching
gem 'connection_pool', '2.5.0'

# Windows timezone fix
platforms :mingw, :mswin, :x64_mingw, :jruby do
  gem 'tzinfo'
  gem 'tzinfo-data'
end
