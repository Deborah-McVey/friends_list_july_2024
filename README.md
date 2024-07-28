"Ruby on Rails Friends List App" by Codemy.com with John Elders of 12-part series from September 2020,
https://www.youtube.com/watch?v=iF8caVyDi5g&list=PLCC34OHNcOtrk3BDsfZwf4GattdLoKCOF&index=1

"Learn Ruby on Rails - Full Course" by freeCodeCamp (John Elder, Codemy) from November 2020. https://www.youtube.com/watch?v=fmyvWz5TUWg&t=9550s

Source code: https://github.com/flatplanet/railsfriends

rails g scaffold friends first_name:string last_name:string email:string phone:string twitter:string

gem devise, bundle i, rails generate devise:install, follow numbered list instructions in terminal, add "config.action_mailer.default_url_options = { host: 'localhost', port: 3000 }" to development and production, rails g devise:views, rails g devise user, rails db:migrate

rails g migration add_user_id_to_friends user_id:integer:index

rails g controller home index


"Git Version Control and Heroku Webhosting - Ruby on Rails Friends List App #12",
https://www.youtube.com/watch?v=XT23tcKRVvI&list=PLCC34OHNcOtrk3BDsfZwf4GattdLoKCOF&index=12

codemy.com/git,
git version control,
git config --global user.name "Deborah McVey",
got config --global user.email "email",
git config --global push.default matching,
git config --global alias.co checkout, 
git init,
git add .,
git commit -am 'descriptive message, example initial commit',
mkdir ~/.ssh for secure,
cd ~/.ssh,
ssh-keygen.exe, 
save,
don't enter passphrase,
ls,
id_rsa id_rsa.pub,
cat id_rsa.pub,
add new ssh key in settings in github,
cd back into your project folder on VS Code,
git remote add origin git@github.com:flatpanet/railsfriends.git,
git branch -M main (change from master to main),
git push -u origin main,
reload on Github,
now if you change a file,
git add .,
git push


