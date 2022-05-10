source "https://rubygems.org"

# Dependencia principal, tanto para local como para github pages.
gem "jekyll", "~> 4.2.2"

# Plugins que estamos usando. Aún se podría limpiar más
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jekyll-include-cache"
#  gem "jekyll-algolia"
end

# Estas siguientes gemas no sé para qué sirven aún
# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Estas siguientes gemas no sé para qué sirven aún
# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Esta dependencia es para que funcione con ruby versión > 3
gem "webrick", "~> 1.7"

# Las dos siguientes dependencias son debido al tema que usamos.
gem "minimal-mistakes-jekyll"
gem "jekyll-remote-theme"