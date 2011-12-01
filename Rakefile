require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('ey_s3_backup', '0.2.0') do |p|
  p.description    = "Backup to S3"
  p.url            = "http://www.3lancers.cz"
  p.author         = "3Lancers"
  p.email          = "info@3lancers.cz"
  p.ignore_pattern = ["tmp/*", "script/*", "nbproject/*"]
  p.development_dependencies = ["rake", "whenever", "aws-s3"]
  p.runtime_dependencies = ["whenever", "aws-s3"]
end

Dir['gem_tasks/**/*.rake'].each { |rake| load rake }
