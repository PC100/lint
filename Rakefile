require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec) do |t|
     t.rspec_opts = "--format html"
     t.rspec_opts = "--out index.html"
end
task :default => :spec
