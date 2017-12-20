# docker-puppetdb
Modified puppetdb from puppetlabs (add puppet master as environment variable)


* Added PUPPETMASTER so the port 8140 check would work if your master name isn't "puppet".
* Using phusion/baseimage instead of Ubuntu base.
