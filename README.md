# Upload files with jQuery File Upload and Paperclip

This is an example app that uses the following gems to upload files for your Rails application:

## Basic idea on how clientside checksumming works (server script agnostic)

http:://localhost:3000/checksum.html (in the public directory)
See: [the checksum.html file](https://github.com/boston-library/jquery-fileupload-rails-paperclip-example/blob/master/public/checksum.html)

## Full version of the application

* [jquery-fileupload-rails](https://github.com/boston-library/jquery-fileupload-rails)
* [Paperclip](https://github.com/thoughtbot/paperclip)

This app also uses [twitter-bootstrap-rails](https://github.com/seyhunak/twitter-bootstrap-rails) but is not required.

This app uses Rails 3.2.8.

## Running the app

    rake db:create
    rake db:migrate
    rails server

Open http:://localhost:3000

## License
The Unlicense (i.e Public Domain)

