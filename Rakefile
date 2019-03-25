require 'html-proofer'

task :build do
  sh "jekyll build"
end

task :serve do
  sh "jekyll serve"
end

task :htmlproofer do
  HTMLProofer.check_directory("./_site",
                    {:url_ignore => [
                      /news/,
                      /http(s?):\/\/(.*)\.freifunk-dresden/,
                      /http(s?):\/\/(.*)\.ffdd/,
                      /http(s?):\/\/127\.0\..*/,
                      /http(s?):\/\/192\.168\..*/,
                      /http(s?):\/\/(.*)\.kosmonautensofa.de/,
                      /http(s?):\/\/(.*)\.konglomerat.org/,
                      /http(s?):\/\/(.*)\.forum.freifunk.net/
                    ]}).run
end

task :trailing_spaces do
  output = `find pages _posts _sass -type f -exec egrep -l \" +$\" {} \\;`
  if output.strip != "" then
    raise "files containing trailing spaces:\n" + output
  end
end

task :test => :build do
  Rake::Task['trailing_spaces'].invoke
  Rake::Task['htmlproofer'].invoke
end

task :clean do
  sh "bundle exec rm -R ./_site || true"
end
