desc "Ejecucion Rock Paper Scissors"
task :default do
  sh "ruby rps.rb"
end

desc "Arrancar el cliente con rock"
task :rock do
  sh %q{curl -v 'http://localhost:9292?choice=rock'}
end

desc "Arrancar el cliente con paper paper"
task :paper do
  sh %q{curl -v 'http://localhost:9292?choice=paper'}
end

desc "Arrancar el cliente con scissors"
task :scissors do
  sh %q{curl -v 'http://localhost:9292?choice=scissors'}
end
