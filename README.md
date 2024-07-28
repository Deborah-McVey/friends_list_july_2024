"Ruby on Rails Friends List App" by Codemy.com with John Elders of 12-part series from September 2020,
https://www.youtube.com/watch?v=iF8caVyDi5g&list=PLCC34OHNcOtrk3BDsfZwf4GattdLoKCOF&index=1

"Learn Ruby on Rails - Full Course" by freeCodeCamp (John Elder, Codemy) from November 2020. https://www.youtube.com/watch?v=fmyvWz5TUWg&t=9550s

Source code: https://github.com/flatplanet/railsfriends

rails g scaffold friends first_name:string last_name:string email:string phone:string twitter:string

gem devise, bundle i, rails generate devise:install, follow numbered list instructions in terminal, add "config.action_mailer.default_url_options = { host: 'localhost', port: 3000 }" to development and production, rails g devise:views, rails g devise user, rails db:migrate

rails g migration add_user_id_to_friends user_id:integer:index

rails g controller home index