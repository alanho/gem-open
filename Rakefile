require "rake/testtask"
require "jeweler"

Rake::TestTask.new do |t|
  t.libs << "test"
  t.libs << "lib"
  t.test_files = FileList["test/**/*_test.rb"]
  t.verbose = true
end

Jeweler::Tasks.new do |gem|
  gem.name = "gem-open"
  gem.version = "0.1.2"
  gem.summary = "Open gems on your favorite editor by running a specific gem command like `gem open nokogiri`."
  gem.email = "fnando.vieira@gmail.com"
  gem.homepage = "http://github.com/fnando/open-gem"
  gem.authors = ["Nando Vieira"]
  gem.files = FileList["lib/**/*", "Rakefile", "README.rdoc"]
end

Jeweler::GemcutterTasks.new
