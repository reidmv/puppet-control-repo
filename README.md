Table of Contents
=================

  * [What You Get From This control-repo](#what-you-get-from-this-control-repo)

# What You Get From This control-repo

This repository is a template control-repo for Puppet.

Two repositories are needed for a complete workflow.

  - A [control-repo](https://github.com/reidmv/puppet-control-repo) (this one) to define environments and what version of code is deployed to them
  - A [puppet-site](https://github.com/reidmv/puppet-site) repo for roles, profiles, any other site-specific modules, and hiera data

The major pieces of content here in the control-repo are:
  - An environment.conf that correctly sets up:
    - A `site/modules` directory for roles, profiles, and any custom modules for your organization.
    - A config\_version script
  - Provided config\_version scripts to output the commit of code that your agent just applied.
  - Sample hiera configuration:
    - `hiera.yaml` to configure a simple hierarchy rooted in `site/data`
  - A Puppetfile that defines:
    - The version of site-specific Puppet code deployed
    - The versions of each module deployed

In a Puppet control-repo, each Git branch represents an environment. To see
which code is deployed to each environment, open the corresponding Git branch.
