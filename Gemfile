source "https://rubygems.org"

# Matches the Jekyll version and plugins used by GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# Ruby 3.x no longer bundles webrick, which `jekyll serve` needs
gem "webrick", "~> 1.8"
