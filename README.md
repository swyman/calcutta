# Calcutta

Eventually this'll be a web app to run Calcutta style auctions

Set it up:
* postgres stuff
  * `brew install postgresql`
  * `brew services start postgresql`
* ruby stuff
  * `rvm install 2.3`
  * `rvm use 2.3`
  * `rvm gemset create calcutta && rvm gemset use calcutta`
* git stuff
  * `git clone git@github.com:swyman/calcutta.git && cd calcutta`
* rails stuff
  * `gem install bundler && bundle`
  * `rake db:setup`
  * `rails s`
