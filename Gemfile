source "https://rubygems.org"
ruby RUBY_VERSION

# Dependency that has a security advisory posted for 1.2.2 - forcing latest safe version
gem "rubyzip", "~> 2.0.0"

# Updated to 1.10.x due to security advisory
gem "nokogiri", ">= 1.10.4"

gem "jekyll", ">= 3.6.3"

source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins

# to use GitHub Pages
# gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
   gem "jekyll-feed"
   gem "jekyll-sitemap"
   gem "jekyll-redirect-from"
   gem "jekyll-seo-tag"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
