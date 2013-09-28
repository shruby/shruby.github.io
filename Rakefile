require 'fileutils'

task default:[:publish]

task :publish do
   comment = Time.now.strftime("RSS update at %m/%d/%Y") + " by #{ENV['USER']}"
   `mv rss.xml rss.previous.xml`
   result = `jekyll build`
   if $?.success?
     FileUtils.cp '_site/rss.xml','./rss.xml'
     `git commit rss.xml -m '#{comment}'`
     `git push` if $?.success?
   end
end
