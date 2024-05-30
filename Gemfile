source 'https://rubygems.org'

ruby '2.7.6'

gem "jekyll", '~> 4.2.0', github: "jekyll/jekyll"
gem 'html-proofer', '>= 3.19.3'
gem 'asciidoctor'
gem 'pygments.rb', '~> 1.1.2'
gem 'rake'
gem 'dotenv'
gem "kramdown-parser-gfm"
gem "liquid-c"
gem 'nokogiri', '~> 1.16', '>= 1.16.5'
gem 'htmlcompressor'
gem 'htmlentities', '~> 4.3', '>= 4.3.4'

group :jekyll_plugins do
  gem 'jekyll-sitemap'
  gem 'jekyll-asciidoc', github: "asciidoctor/jekyll-asciidoc"
  gem 'jekyll-algolia', '~> 1.7', '>= 1.7.0' # Used by `Update Algolia Index` CI step
  gem 'jekyll-last-modified-at' # Used for page metadata
end

group :test, :development do
  gem 'pronto'
  gem 'pronto-markdownlint'
end
