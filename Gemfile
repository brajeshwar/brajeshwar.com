source "https://rubygems.org"
gem "jekyll", "~> 4.2.0"
group :jekyll_plugins do
  gem 'jekyll-feed', '~> 0.13'
  gem 'jekyll-sitemap', '~> 1.4'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]