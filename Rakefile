desc "Publicar en GitHub los apuntes de PL"
task :default do
  sh "git ci -am 2019 && git push"
end

desc "serve locally"
task :serve do
  sh "bundle exec jekyll serve --future --watch --host 0.0.0.0 --port 8082"
end

