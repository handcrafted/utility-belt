require 'rubygems'
require 'rake'
require 'sass'
require 'lib/handcrafted-utilities/sass_extensions'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "handcrafted-utilities"
    gem.summary = %Q{Handcrafted's Compass utilities}
    gem.description = %Q{Handcrafted's Compass utilities}
    gem.email = "adam@gethandcrafted.com"
    gem.homepage = "http://github.com/handcrafted/handcrafted-utilities"
    gem.authors = ["Adam Stacoviak"]
    gem.has_rdoc = false
    gem.add_dependency('compass', '>= 0.8.16')
    gem.files = []
    gem.files << "README.textile"
    gem.files << "VERSION"
    gem.files << "Rakefile"
    gem.files += Dir.glob("lib/**/*")
    gem.files += Dir.glob("sass/**/*")
  end
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end