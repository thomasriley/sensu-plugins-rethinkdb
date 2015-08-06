## Sensu-Plugins-mysql

[ ![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-rethinkdb.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-rethinkdb)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-rethinkdb.svg)](http://badge.fury.io/rb/sensu-plugins-rethinkdb)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-rethinkdb/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-rethinkdb)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-rethinkdb/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-rethinkdb)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-rethinkdb.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-rethinkdb)
[![Codeship Status for sensu-plugins/sensu-plugins-rethinkdb](https://codeship.com/projects/266116c0-e896-0132-af9a-62885e5c211b/status?branch=master)](https://codeship.com/projects/82837)

## Functionality

## Files
 * bin/check-rethinkdb-replication-status.rb
 * bin/metrics-rethinkdb-count.rb
 * bin/metrics-rethinkdb.rb
 
## Usage

**metrics-rethinkdb**
```
{
    "rethinkdb":{
        "hostname": "localhost",
        "port": "",
        "username": "sensu_user",
        "password": "sensu_user_pass"
    }
}
```

## Installation

[Installation and Setup](http://sensu-plugins.io/docs/installation_instructions.html)

## Notes