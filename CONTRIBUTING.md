# Set up build environment

    gem install gem-release

# Releasing new versions

Documentation referred from http://guides.rubygems.org/publishing/ and https://bundler.io/v1.13/guides/creating_gem

```sh
gem bump
git push
rm *.gem
gem build lightning_sites.gemspec
gem push lightning_sites-*.gem
```

# Contributing
Make sure to update the CHANGELOG.MD whenever you submit a pull request. 

