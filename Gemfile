source "https://rubygems.org"

gem "middleman", "~>3.4.0"
gem "middleman-livereload", "~> 3.1.0"

gem "bitters"
gem "bourbon"
gem "neat"
gem "nokogiri"

source "https://rails-assets.org" do
  gem "rails-assets-jquery"
  gem "rails-assets-moment"
end

gem "middleman-s3_sync", "~>3.3.0"
gem "middleman-search_engine_sitemap"
gem "middleman-cloudfront"
gem "unf"

group :development do
  gem "rspec"
  gem "capybara"
  gem "launchy"
end

# Temporary workaround for fog error that blows up s3_sync
gem "fog-core", "1.34.0"
