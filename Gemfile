source :rubygems

if RUBY_PLATFORM =~ /mswin/
  gem 'win32-pipe'
else
  gem 'mkfifo'
end

group :test do
  gem 'rspec'
  gem 'rake'
end

group :development do
  gem 'pry'
end
