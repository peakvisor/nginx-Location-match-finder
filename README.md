# Python utility to find location match for given URI
#### Table of Contents
  - [Introduction](#introduction)
  - [Included content](#included-content)
  - [Requirements](#requirements)
  - [Usage](#usage)

## Introduction
The "location_match_finder" utility searches for a location that matches a given request.

## Included content

## Requirements
To successfully parse the Nginx configuration file, all [location](http://nginx.org/en/docs/http/ngx_http_core_module.html#location) directives must be converted to the following format:
  - A line with a first-level directive must start with 4 spaces or 1 tab character
  - A line with a second-level directive must start with 8 spaces or 2 tab characters
  - A line with a third-level directive must start with 12 spaces or 3 tab characters
  - All processed directives must be in a single file ([include](http://nginx.org/ru/docs/ngx_core_module.html#include) directive are not supported)

See example [nginx-config-example.conf](tests/nginx-config-example.conf)

## Usage
