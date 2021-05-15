# Journal

## The Ground Work
**Installing Rspec** First things first, Rails comes with minitest as the default testing tool.  I'm sure it's great, but all the Ruby testing I've been exposed to has used rspec, so that's what I'm going to use for this project as well.


**GitHub Actions** I like to set up CI/CD for a project early because I think deployments should be as boring as possible - when you find yourself needing to delay deployments until the off hours you know that you have a bit of a problem.  Well tested code gives confidence, as do established, well worn deployment strategies.

Chris Oliver has a great video about using [Github actions for Rails CI](https://gorails.com/episodes/github-actions-continuous-integration-ruby-on-rails) - I'm going to work off of his ci.yml because I like the defaults he chooses - ultimately I will deploy this app to my personal VPS which will be running Ubuntu and Postgres which is inline with what he choses.

This does mean that I'm going to rip off the bandaid early and replace the default SQLite database with Postgres.