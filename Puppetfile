# This is a Puppetfile, which describes a collection of Puppet modules. For
# format and syntax examples, see one of the following resources:
#
# https://github.com/rodjek/librarian-puppet/blob/master/README.md
# https://github.com/adrienthebo/r10k/blob/master/README.markdown
#

##
# SITE-SPECIFIC CONTENT
#
# Should be assigned a specific version; tag or commit (except when developing)
#
mod 'site',
  :install_path => '.',
  :git => 'https://github.com/reidmv/puppet-site.git',
  :ref => 'master'

##
# MODULES
#
# Each module here should be assigned a specific version; tag or commit (except
# when developing)
#
mod 'puppetlabs/stdlib',
  :git => 'https://github.com/puppetlabs/puppetlabs-stdlib.git',
  :ref => '4.20.0'
mod 'lwf/remote_file',
  :git => 'https://github.com/lwf/puppet-remote_file.git',
  :ref => 'v1.1.3'
mod 'puppetlabs/concat',
  :git => 'https://github.com/puppetlabs/puppetlabs-concat.git',
  :ref => '4.1.0'
mod 'puppetlabs/powershell',
  :git => 'https://github.com/puppetlabs/puppetlabs-powershell.git',
  :ref => '2.1.2'
mod 'puppetlabs/inifile',
  :git => 'https://github.com/puppetlabs/puppetlabs-inifile.git',
  :ref => '2.0.0'
mod 'puppetlabs/puppet_agent',
  :git => 'https://github.com/puppetlabs/puppetlabs-puppet_agent.git',
  :ref => '1.4.1'
