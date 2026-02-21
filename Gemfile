source "https://rubygems.org"

# Jekyll
gem "jekyll", "~> 4.3"

# Minima theme
gem "minima", "~> 2.5"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.8"
end

# Windows-specific dependencies
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
