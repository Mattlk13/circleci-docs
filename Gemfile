source 'https://rubygems.org'

ruby '2.6.3'

gem 'jekyll', "3.8.5"
gem 'html-proofer', '>= 3.9.3'
gem 'jekyll-sitemap'

gem 'jekyll-assets', '>= 3.0.12'
# jekyll-assets depends on sprockets, which depends on rack, which has two
# security vulnerabilities prior to 2.0.6.
# https://nvd.nist.gov/vuln/detail/CVE-2018-16471
# https://nvd.nist.gov/vuln/detail/CVE-2018-16470
gem "rack", ">= 2.0.6"

group :jekyll_plugins do
  gem 'jekyll-algolia', '~> 1.0'
end
