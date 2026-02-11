source "https://rubygems.org"

# La gema 'github-pages' gestiona todas las dependencias por ti
gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Soporte para Windows (tu entorno local)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Optimizador de rendimiento para Windows [cite: 111]
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]