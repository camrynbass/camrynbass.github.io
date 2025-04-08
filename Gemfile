# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 4.3.4"
gem "webrick", "~> 1.7" # Required for local development
gem "jekyll-paginate", "~> 1.1.0" # Pagination plugin
gem "jekyll-include-cache", "~> 0.2.1" # Include-cache plugin
gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
