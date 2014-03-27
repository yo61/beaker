# Beaker

Puppet Labs cloud enabled acceptance testing tool.
## Docker support ##

This option allows for testing against Docker containers.  The base container is
named by the `base` key.

  HOSTS:
    ubuntu-12-10:
      platform: ubuntu-12.10-x64
      image: ubuntu:12.10
      hypervisor: docker
  CONFIG:
    type: foss

Currently this just starts an sshd, so is only useful for 'puppet apply' style
testing.


#Documentation

Documentation for Beaker can be found online at the
[Beaker Wiki](https://github.com/puppetlabs/beaker/wiki).

#Beaker API

[RubyDoc Beaker Documentation Server](http://rubydoc.info/github/puppetlabs/beaker/frames)

#License

See [LICENSE](LICENSE) file.

#Support

Please log tickets and issues at our [Beaker Issue Tracker](https://github.com/puppetlabs/beaker/issues).  In addition there is an active #puppet-dev channel on Freenode.

We use semantic version numbers for our releases, and recommend that users stay
as up-to-date as possible by upgrading to patch releases and minor releases as
they become available.
