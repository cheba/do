## 0.1.5 (Not yet released)

* Append now add \n at the end of line if not present
* Added options :recursive to download and upload methods
* Added a new method for execute local task inside a remote server

## 0.1.4 - August 31, 2011

* Added support to auto completion

## 0.1.3 - August 26, 2011

* Fixed a small bug in option parser

## 0.1.2 - August 24, 2011

* Tiny Regex change, and aliasing :on => :webserver for :in => :webserver [Thanks to Doug Johnson]
* :on is now an alias for :in [Thanks to Doug Johnson]
* Removed trailing colon from /password:/ regex [Thanks to Doug Johnson]
* Updated net-ssh dependency to latest version

## 0.1.1 - August 14, 2011

* Remove rake dependency
* Simpler way to manage remote servers
* Simpler way to manage local machine
* Argument parser
* Fixed problem with ordered hash
* Allow to run dependencies in same contest

## 0.0.2 - August 9, 2011

* Added `doit do:setup` task that generate a template in `~./do/dorc`
* Improved support of plugins
* Added `doit download[http://raw.github...]` task which download and update for you a given rake task
* Improved output messages
