require 'open-uri'

desc "This task is called by the Heroku cron add-on"
task :call_page do
  open("http://trylogo.heroku.com").read
end
