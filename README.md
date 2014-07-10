# Lyon.rb website

This repository holds the Middleman source code for [Lyon.rb website](http://lyonrb.fr).

To create a new blog post: `middleman article "My Post title"`

## Usage

1. Clone this repository: `git clone git@github.com:lyonrb/website.git lyonrb-website`
2. Install Ruby requirements: `bundle install`
3. Install Javascript requirements: `bower install`
3. Run server for development: `bundle exec middleman server`
4. Build static website: `bundle exec middleman build`
5. Deploy !: `bundle exec middleman deploy`

### Data

Data about members, meetups & conferences and companies is stored as YAML files. Available attributes are:

* `name`: regular human-readable name
* `website`: URL
* `logo`: image URL
* `email`: email address
* `github`: username only
* `twitter`: username only
* `meetup`: username only
* `vimeo`: username only
* `youtube`: username only
* `confreaks`: event slug
* `mailinglist`: URL
* `tags`: array of strings

Logos/avatars are fetched automatically from [Gravatar](https://gravatar.com) or [GitHub API](http://developer.github.com/v3).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

* Michael Baudino (@michaelbaudino)
* Laurie Guetat (@laurieguetat)
* Camille Appert (@cappert)

## License

See LICENSE.md file.
