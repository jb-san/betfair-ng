# Betfair::Ng

A client gem for interfacing with the new Betfair-(n)ext(g)eneration API

## Installation

Add this line to your application's Gemfile:

    gem 'betfair-ng'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install betfair-ng

## Usage

```ruby
require 'betfair-ng'

Client = Betfair::Client.new('Username','s3cr3t',:uk)

Client.get_account_details
# returns a response object that has all the AccountDetailsResponse fields


```
## Contributing

1. Fork it ( http://github.com/<my-github-username>/betfair-ng/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
