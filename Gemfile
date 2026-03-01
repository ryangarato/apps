ruby "3.2.2"
source "https://rubygems.org"

gem "ffi", "~> 1.15"

gem "github-pages", group: :jekyll_plugins

# patch vulnerable dependencies
# Faraday release 2.8.1 has CVE-2026-25765; bump to latest 2.x that supports Ruby 3
gem "faraday", ">= 2.14.1"
# Nokogiri prior to 1.19 contains multiple GHSA advisories; upgrade to safe release
gem "nokogiri", ">= 1.19.1"

group :jekyll_plugins do
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
end