# Water.css Jekyll theme (Work in Progress)

This is a Jekyll theme for GitHub Pages with simple styling from [Water.css](https://watercss.kognise.dev)
## Installation
### GitHub Pages
Add this line to your `_config.yml`. You can also fork this repo.

```yaml
remote-theme: "luke2m/watercss-jekyll@latest"
```
### Other platforms (Self hosted, Netlify, GitLab Pages, etc.
Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "water-css"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: water-css
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install water-css


## Usage

This theme is meant for quick repo docs, not blogs or personal sites. I may make a theme for that purpose sometime soon. 
Configurable variables (in `_config.yml`):
- Light, Dark, or Automatic theme
- Title and description
- Show or hide download and source links
- Change View on GitHub to another name
- Change download link
- Add privacy friendly analytics with [GoatCounter](https://www.goatcounter.com)
- More customization will be coming soon.
## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/luke2m/watercss-jekyll. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
## TODO
- [x] Customize or disable download and code buttons
- [ ] Make easier for non-github users
- [x] Publish Ruby Gem
- [ ] Make version for personal sites/blogs

