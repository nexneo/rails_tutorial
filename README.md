Based on https://www.railstutorial.org

Run the following commands in the console below:

1. `cd ~/workspace/rails_tutorial`
2. `cp config/database.yml.example config/database.yml`
3. `bundle install`
4. `bundle exec rake db:migrate`
5. `bundle exec rails server`

Run tests

1. `bundle exec rake db:test:prepare`
2. `bundle exec rspec spec`


Features to add:
----

1. As a first signed up user, I becomes super admin
2. As a super admin I can delete other users
3. As a super admin I can approve/reject micropost
