# Chef cookbook for Statsdaemon

[![Build Status](https://travis-ci.org/mburns/cookbook-statsdaemon-vimeo.svg)](https://travis-ci.org/mburns/cookbook-statsdaemon-vimeo)
[![Chef cookbook](https://img.shields.io/cookbook/v/statsdaemon-vimeo.svg)](https://supermarket.chef.io/cookbooks/statsdaemon-vimeo)

## Description

Chef cookbook for [statsdaemon](https://github.com/vimeo/statsdaemon), a statsd
daemon written in go by vimeo.

## Requirements

### Platform

* Debian
* Ubuntu

**Notes**: This cookbook has been tested on Debian 7.6. It may work on other
platforms with or without modification. Please [report
issues](https://github.com/mburns/cookbook-statsdaemon-vimeo/issues) any
additional platforms so they can be added.

## Usage

### statsdaemon-vimeo::default

Just include `statsdaemon-vimeo` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[statsdaemon-vimeo]"
  ]
}
```

## Supermarket share

    knife supermarket share statsdaemon-vimeo "Monitoring & Trending"

## License

This cookbook is released under the MIT License. See the bundled LICENSE file
for details.
