desc "Generate the rubyonrails.org website"
task :generate do
  rm_f "_site/sitemap.xml"
  rm_f "sitemap.xml"
  system "jekyll build"
  cp "_site/sitemap.xml", "sitemap.xml"
end