# webhook
This is a simple script, that catches webhooks from github and attempts to build it, posting an issue to the repo if it fails, or closing an existing one if it's still open.

## Requirements
Required:

* bash
* netcat-traditional
* git

Optional:

* ghi rubygem
* proper email

## Installation
Just run `./server` and forward a url into port 8081.

Alternatively, `vagrant up` and forward port 8081.

Setup this url endpoint in the webhooks section of github.

## Usage
1. Push to Github.
1. Fix any issues it reports.
1. ???
1. Profit!
