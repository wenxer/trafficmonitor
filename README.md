# Traffic Monitor
version 0.0.3
gem help you analysis traffic per ip with port

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'trafficmonitor'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install trafficmonitor

## Usage

```ruby
    require 'trafficmonitor'
    puts Trafficmonitor::VERSION
    puts Trafficmonitor::Iftop.connections 'eth0'
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/traffic-monitor/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
