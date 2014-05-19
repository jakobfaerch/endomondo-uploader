Endomondo uploader
==================

Uploads a single tcx file to Endomondo as a new workout.
Type of workout is set as kayaking.

Usage
-----
Rename auth_template.yml to auth.yml and enter your endomondo username and password.

Install bundler
> gem install bundler

Run the script as
> bundle install&&bundle exec ruby endomondo_upload.rb <path to tcx file>