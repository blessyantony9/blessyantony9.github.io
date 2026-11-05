source "https://rubygems.org"

# This repo builds natively on GitHub Pages (no Actions workflow needed).
# Run locally with: bundle exec jekyll serve

gem "github-pages", group: :jekyll_plugins

gem "wdm", "~> 0.1.0" if Gem.win_platform?
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw]
gem "webrick"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end
