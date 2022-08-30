source "https://rubygems.org"

gem "jekyll-theme-simplex-v2", "~> 0.9.8.16"
gem "github-pages", group: :jekyll_plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

if Gem::Version.new(RUBY_VERSION) >= Gem::Version.new("3.0.0")
  gem "webrick"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]


