require 'rubygems'
require 'rake'

desc "Compile everything"
task :compile do
  sh "coffee --compile --output js/compiled/ js/coffeescript/"
  sh "compass compile"
  sh "jekyll"
end

desc "Watch-compile jekyll site"
task :jekyll do
  sh "jekyll --auto --server"
end

desc "Watch-compile coffeescript"
task :coffee do
  sh "coffee --compile --watch --output js/compiled/ js/coffeescript/"
end

desc "Watch-compile SCSS with Compass"
task :compass do
  sh "compass watch"
end

desc "Deploy site"
task :publish do
  sh "rm -rf _site js/compiled css/compiled"
  sh "coffee --compile --output js/compiled/ js/coffeescript/"
  sh "compass compile --output-style compressed"
  sh "jekyll --lsi"
end