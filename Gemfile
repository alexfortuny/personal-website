source "https://rubygems.org"

# RUN SERVER
# bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
gem "jekyll", "~> 3.9.0"

# THEMES
gem "minima", "~> 2.5.1"
# gem "no-style-please"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", "~> 227", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :platforms => [:mingw, :x64_mingw, :mswin]

# kramdown v2 ships without the gfm parser by default. If you're using
# kramdown v1, comment out this line.
gem "kramdown-parser-gfm"

# webrick
gem "webrick", "~> 1.7"
