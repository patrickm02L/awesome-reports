# awesome-reports
A simple jekyll template made for publishing a web-based report rather than a PDF.

## Editing
If you clone this template and want to edit it locally be sure to comment out (using the # mark) or delete the url from the baseurl in the `_config.yml` file. If you publish a version on gh-pages you will need to copy the that url into the baseurl to correctly map to your site.  

## Run Locally
Navigate to the directory where you've saved awesome-reports then run `bundle install`. The site runs locally at localhost:4000 when you run `jekyll serve --watch.`

To ensure the proper jekyll is running run Jekyll with `bundle exec jekyll install`.

## Trouble Shooting
If you're having trouble running you may have to `gem install rails -v 3.2.1`, then `bundle exec jekyll install`.

###Inspired by
[Code for America 2015 Fellows, Team RVA Report ](https://github.com/codeforamerica/rva) 
