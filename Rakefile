require 'rake'

task :test do
  puts "Using RUBY_VERSION: #{RUBY_VERSION}"

#  ENV.keys.sort.each do |key|
#    puts "#{key}: #{ENV[key]}"
#  end

  1.upto(100) do
    sleep(0.01)
    print 'WAT!'
    $stdout.flush
  end
  # foo!
  exit rand(2)
end

task :default => :test
