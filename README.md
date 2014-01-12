# intervals

This gem is a simple Ruby wrapper for the intervals REST API.

To learn more, check out the [intervals API Documentation][http://www.myintervals.com/api/].

## Installation

Add this line to your application's Gemfile:

    gem 'intervals-ruby'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install intervals-ruby

## Usage

In order to access intervals, you need to provide your [API key][].


```ruby
intervals.configure do |client|
  client.api_key = 'your_intervals_api_key'
end
```
## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

[ActiveResource]: http://api.rubyonrails.org/classes/ActiveResource/Base.html
[intervals API Documentation]: http://www.myintervals.com/api/