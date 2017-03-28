source 'http://rubygems.org'

bundler_version=Gem::Version.new(File.read(".bundler-version"))
if Gem::Version.new(Bundler::VERSION) < bundler_version
  exec("gem install bundler -v \"#{bundler_version}\" && bundle _#{bundler_version}_ install")
end

gem 'puppet'
gem 'librarian-puppet'
gem 'hiera-eyaml'
