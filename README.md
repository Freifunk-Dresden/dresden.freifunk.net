# FFDD Website [![Build Status](https://drone.envs.net/api/badges/freifunk-dresden/dresden.freifunk.net/status.svg)](https://drone.envs.net/freifunk-dresden/dresden.freifunk.net)

[freifunk-dresden.de](https://freifunk-dresden.de/) | [dresden.freifunk.net](http://dresden.freifunk.net/)

## Dependencies
 - Install a javascript runtime, e.g. nodejs
 - Install bundle by running `gem install bundle`
 - Install the dependencies by running `bundle`

```bash
apt install -y git nodejs
```

**ruby 2.2.0**

```bash
curl -L https://get.rvm.io | bash -s stable --ruby=2.2.0
```

**bundler**

```bash
gem install bundler -v 1.17.3
```

## Install
```bash
git clone https://github.com/Freifunk-Dresden/Blog.git /srv/Blog
git clone https://github.com/Freifunk-Dresden/dresden.freifunk.net.git /srv/dresden.freifunk.net
cd /srv/dresden.freifunk.net/
bundle install
```

## Info
On Ubuntu you might need to change the next lines in the 'Rakefile'

*Line 4:* `sh "jekyll build"` to:
```bash
    sh "bundle exec jekyll build"
```
*Line 8:* `sh "jekyll serve"` to:
```bash
    sh "bundle exec jekyll serve"
```

## Building
 - Use `rake build`. This will build the website to the `_site` directory

## Serving (to work locally)
 - Use `rake serve`. This watches files for changes and serves the website on http://0.0.0.0:4000/

## Testing
 - Use `rake test`

State of the current master branch, powered by Travis-CI:
[![Build Status](https://travis-ci.com/Freifunk-Dresden/dresden.freifunk.net.svg?branch=master)](https://travis-ci.com/Freifunk-Dresden/dresden.freifunk.net)

## Deployment
Simply `git push` to the master branch. There's a hook that will automatically deploy it to [dresden.freifunk.net](http://dresden.freifunk.net/)
