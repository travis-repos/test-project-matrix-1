require 'rake'

task :test do
  puts "Using RUBY_VERSION: #{RUBY_VERSION}"

#  ENV.keys.sort.each do |key|
#    puts "#{key}: #{ENV[key]}"
#  end

  1.upto(100) do
    sleep(0.01)
    putc '.'
    $stdout.flush
  end
  puts "some \0 null \000 characters \u0000 in \x00 here"
  puts "some non-utf-8 bytes here \xE2 \xC3 here"
  # foo!
  exit rand(2)
end

task :default => :test
