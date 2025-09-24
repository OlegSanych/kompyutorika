# Gemfile
source "https://rubygems.org"

gem "jekyll", "~> 4.4"
gem "jekyll-theme-chirpy", "~> 7.3"

group :jekyll_plugins do
  gem "jekyll-archives"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-include-cache"
  gem "jekyll-compose"
end

# Для production сборки исключаем development и test группы
group :development, :test do
  gem "html-proofer", "~> 5.0"
  gem "w3c_validators", "~> 1.3"
end

# Явно указываем версии для стабильности
gem "webrick", "~> 1.7"
gem "tzinfo", "~> 2.0"
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
