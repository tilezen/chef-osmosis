CHANGELOG
=========

0.6.0
-----
* rewrite to use ark
* vagrant to ubuntu 14.04

0.5.2
-----
* make install from source default

0.5.1
-----
* when installing from source, create /usr/bin/osmosis symlink by default

0.5.0
-----
* pkg install should use common repo

0.4.3
-----
* symlink into /usr/bin option
* explicit java::default

0.4.1
-----
* add `default[:osmosis][:symlink]` option: creates a symlink from 
`node[:osmosis][:installdir]/bin/osmosis` to `/usr/bin/osmosis` when true.
Defaults to nil.

0.4.0
-----
* supports install from pkg or tgz
