# encoding: utf-8

require 'rake/gempackagetask'

load File.dirname(__FILE__) + '/achoo-plugin-homescreen.gemspec'

namespace 'build' do

  Rake::GemPackageTask.new(Spec) do |pkg|
    pkg.need_tar = true
  end

end

desc 'Remove generated files and folders'
task :clean => ['build:clobber_package']
