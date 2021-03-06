if RUBY_VERSION =~ /1.9/
  Encoding.default_external = Encoding::UTF_8
  Encoding.default_internal = Encoding::UTF_8
end

source "https://rubygems.org"

gem "rack"
gem "sinatra", "~> 1.3.2"
gem "rake"

# For managing our Ruby load path.
gem "pathological"

gem "resque"

# For writing CSS more conveniently.
gem "sass", "~> 3.1.16"

# For managing compiling and caching assets
gem "pinion"

# Really nice scss mixin library.
gem "bourbon"

# For JS minification
gem "uglifier"

# We're pulling in our own grit fork with bugfixes.
gem "grit", :github => "LCChronicles/barkeep-grit", :ref => "e208db829b4190346c00d751af9e67fc8470ceee"
gem "json"
gem "sequel"
gem "mysql2"
gem "thin"
gem "pygments.rb", "0.6.0"
gem "redis"
gem "ruby-openid"
gem "oauth2"
gem "redcarpet", "= 2.0.0b3"
gem "coffee-script"
gem "methodchain"
gem "sinatra-contrib" # For Sinatra::Reloader

# Clockwork is a cron implementation in Ruby. We use it for periodically fetching new commits.
gem "clockwork"

# For running all of our background processes together from a single developer-friendly command.
gem "foreman"

# For sending emails.
gem "pony"

# For rendering erb outside of views.
gem "tilt"

# For generating unified diffs
gem "diff-lcs"

# For validating repo uris
gem "addressable"

# For nicely indented heredocs
gem "dedent"

 # For making exception backtraces more friendly during development.
gem "backtrace_shortener"

# For running our app in production, using multiple workers.
gem "unicorn"

# for templates that can be rendered client and server side
gem "mustache"

# For executing javascript inside Ruby (for compiling coffeescript).
gem "therubyracer"

# For scripting system setup.
gem "terraform"

gem "nokogiri"
gem "fezzik"

group :test do
  # NOTE(caleb): require rr >= 1.0.3 and scope >= 0.2.3 for mutual compatibility
  gem "rr", ">= 1.0.3"
  gem "scope", ">= 0.2.3"
  gem "rack-test"
end

group :development do
  gem "awesome_print"
  gem "statusz" # For the deploy information status page
end
