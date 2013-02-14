# TheComments

TODO: Write a gem description

```ruby
gem 'awesome_nested_set'
gem 'the_sortable_tree'
gem 'state_machine'
gem 'sanitize'
```

## Installation

```ruby
  gem 'the_comments'

  bundle exec rails g model comment --migration=false

  bundle exec rake the_comments_engine:install:migrations

  class Blog < ActiveRecord::Base
    has_many :comments, as: :commentable
  end

  class Comment < ActiveRecord::Base
    include TheCommentModel
  end

```

Add this line to your application's Gemfile:

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install the_comments

## Usage

TODO: Write usage instructions here

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request