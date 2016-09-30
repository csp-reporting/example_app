## What is this example app?
This is a Ruby on Rails 5 example app generating CSP(Content Security Policy)
reports due to a quite locked down CSP Policy. It uses Twitters Secure Headers
gem to configure the CSP Policy. It's defined in
`config/initializers/secure_headers.rb`.

## Installation
```
git clone https://github.com/csp-reporting/example_app.git
cd example_app
bundle install
source .env
bundle exec rails s
```

## Configuration
Edit the .env file to suit by which URI your report recieving
application is accessible.

## License
MIT
