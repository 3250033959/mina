# Mina

Really fast deployer and server automation tool.

## Warning

**This is a readme of the current master, version 1.0.0.beta1. If you are using older mina (pre 0.3) please take a look at [0.3 readme](https://github.com/mina-deploy/mina/blob/v0.3.8/Readme.md)**


Mina works really fast because it's a deploy Bash script generator. It
generates an entire procedure as a Bash script and runs it remotely in the
server.

Compare this to the likes of [Vlad](https://github.com/seattlerb/vlad) or
[Capistrano](https://github.com/capistrano/capistrano), where each command
is run separately on their own SSH sessions. Mina only creates *one* SSH
session per deploy, minimizing the SSH connection overhead.

    $ gem install mina
    $ mina

[![Build Status](https://travis-ci.org/mina-deploy/mina.svg?branch=master)](https://travis-ci.org/mina-deploy/mina)
[![Gem Version](https://badge.fury.io/rb/mina.svg)](http://badge.fury.io/rb/mina)

Documentation
----------------

For quick start check out [Getting starting guide](https://github.com/mina-deploy/mina/wiki/Getting-Started)


For other documentation please visit the [wiki](https://github.com/mina-deploy/mina/wiki)

Acknowledgements
----------------

© 2012-2015, Nadarei.  
2015-2016, Infinum.  
Released under the [MIT License](http://www.opensource.org/licenses/mit-license.php).

Mina is authored [Rico Sta. Cruz][rsc] and [Michael Galero][mg] with help from its [contributors][c] and their startup, [Nadarei][nd].  
It is maintained by [Stjepan Hadjić][sh] and [Gabrijel Škoro][gs] and sponsored by [Infinum][inf].

Stjepan:

* [Github](https://github.com/d4be4st) (@d4be4st)
* [Twitter](https://twitter.com/_Beast_) (@_Beast_)

Gabrijel:

* [Github](https://github.com/gabskoro) (@gabskoro)
* [Twitter](https://twitter.com/gabskoro) (@gabskoro)

Rico:

 * [My website](http://ricostacruz.com) (ricostacruz.com)
 * [Github](http://github.com/rstacruz) (@rstacruz)
 * [Twitter](http://twitter.com/rstacruz) (@rstacruz)

Michael:

 * [My website][mg] (michaelgalero.com)
 * [Github](http://github.com/mikong) (@mikong)

Nadrei:

 * [Nadarei](http://nadarei.co) (nadarei.co)
 * [Github](http://github.com/nadarei) (@nadarei)

[rsc]: http://ricostacruz.com
[mg]:  http://devblog.michaelgalero.com/
[c]:   http://github.com/mina-deploy/mina/graphs/contributors
[nd]:  http://nadarei.co
[sh]:  
