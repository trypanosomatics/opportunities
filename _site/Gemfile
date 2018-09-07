if ENV['CI']
    ruby RUBY_VERSION
else
  # TODO: read from the gemspec somehow? (Apparently Bundler will do that
  # in Bundler 2.x)
  ruby File.read('.ruby-version') rescue RUBY_VERSION
end
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
