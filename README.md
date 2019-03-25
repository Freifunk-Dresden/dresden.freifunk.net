FFDD website
============================
[dresden.freifunk.net](http://dresden.freifunk.net)

## Dependencies
 - Install a javascript runtime, e.g. nodejs
 - Install bundle by running `gem install bundle`
 - Install the dependencies by running `bundle`

## Building
 - Use `rake build`. This will build the website to the `_site` directory

## Serving (to work locally)
 - Use `rake serve`. This watches files for changes and serves the website on http://0.0.0.0:4000/

## Testing
 - Use `rake test`
State of the current master branch, powered by Travis-CI:
[![Build Status](https://travis-ci.org/Freifunk-Dresden/dresden.freifunk.net.svg?branch=master)](https://travis-ci.org/Freifunk-Dresden/dresden.freifunk.net)

## Deployment
Simply `git push` to the master branch. There's a hook that will automatically deploy it to [dresden.freifunk.net](dresden.freifunk.net)
