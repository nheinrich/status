status
=======

- bundle install
- jekyll serve --baseurl ''

Note: The baseurl is set to '/status' in the config. This setting is necessary
for the live site to work. To accommodate developing locally you can pass an
empty baseurl to `jekyll serve` and the site will run as expected
(on http://localhost:4000).
