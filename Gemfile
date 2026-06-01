source "https://rubygems.org"

# Core Jekyll
gem "jekyll", "~> 4.3"

# Default theme
gem "minima", "~> 2.5"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
end

# Windows compatibility (safe to keep even if not used)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Windows file watcher (safe to ignore on macOS but harmless)
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]