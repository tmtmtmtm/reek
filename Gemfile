source 'https://rubygems.org'

gemspec

ruby RUBY_VERSION

group :development do
  gem 'aruba',                 '~> 1.0'
  gem 'codeclimate-engine-rb', '~> 0.4.0'
  gem 'cucumber',              ['>= 4.0', '< 6.0']
  gem 'kramdown',              '~> 2.1'
  gem 'kramdown-parser-gfm',   '~> 1.0'
  gem 'rake',                  '~> 13.0'
  gem 'rspec',                 '~> 3.0'
  gem 'rspec-benchmark',       '~> 0.6.0'
  gem 'rubocop',               '~> 1.7.0'
  gem 'rubocop-performance',   '~> 1.9.1'
  gem 'rubocop-rspec',         '~> 2.1.0'
  gem 'simplecov',             ['>= 0.18.0', '< 0.21.0']
  gem 'yard',                  '~> 0.9.5'

  platforms :mri do
    gem 'redcarpet', '~> 3.4'
  end
end

group :debugging do
  gem 'pry', '~> 0.13.0'
end
