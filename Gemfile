source "https://rubygems.org"

gem "rails", ">= 4.0"

group :development do

  gem "bundler"
  if RUBY_VERSION >= "2.3"
    gem "jeweler", ">= 2.1.2", platform: [:ruby_23, :ruby_24, :ruby_25]
  end


  #gem "json", ">= 1.9"
  gem "pry-byebug"

  gem "rspec", ">= 3"
  gem "nokogiri" # used to test html output

  if RUBY_VERSION >= "2.5"
    gem "sqlite3", "~> 1.4", platform: [:ruby_25]
  else
    gem "sqlite3", "~> 1.3.6"
  end
  gem "sequel"

  group :mongo do
    gem "mongoid"
    #gem "mongo_mapper", "~> 0.13.0"
    gem "bson"
    gem "bson_ext"
  end

end
