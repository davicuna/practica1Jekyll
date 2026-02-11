source "https://rubygems.org"

# Hemos comentado la gema de jekyll individual para usar el paquete oficial de GitHub Pages
# gem "jekyll", "~> 4.4.1"

# Esta es la gema que debes usar para que GitHub Actions no falle al compilar [cite: 107, 108]
gem "github-pages", group: :jekyll_plugins

# Tema por defecto para sitios Jekyll [cite: 107]
gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Soporte para Windows (necesario para tu entorno local) [cite: 110]
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Optimizador de rendimiento para Windows [cite: 111]
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]