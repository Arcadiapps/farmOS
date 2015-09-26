farmOS
======

A Drupal installation profile for farms. http://drupal.org/project/farm

This project aims to provide a Drupal distribution for use in agriculture. It
comes pre-packaged with a set of farm-related modules. For more information,
visit http://farmos.org

Drupal.org is the location of the canonical repositories and mainline branches.
Github.org is also used as a mirror, and for some of the more experimental
development. See http://github.org/farmOS for a list of repositories.

INSTALLATION
------------

farmOS is a [Drupal distribution](http://www.drupal.org/documentation/build/distributions),
so it is essentially a Drupal codebase that combines Drupal core with a set of
pre-selected contributed modules.

If you are downloading farmOS from drupal.org, then it is pre-built and
ready to go. Just drop it into a hosted web server environment and it will work
the same as Drupal. For more information on installing Drupal, see the official
[Installing Drupal](http://www.drupal.org/documentation/install) documentation.

During the installation, you will be given a choice of which "Installation
Profile" you want your site to use. Choose "farmOS" and the modules
mentioned above will be automatically installed.

**Drush Make**

You can also build the distribution yourself using Drush Make. Simply grab the
file called build-farm.make from the repository, pop it into a directory, and
run the following command:

    drush make build-farm.make farm

MAINTAINERS
-----------

Current maintainers:
 * Michael Stenta (m.stenta) - https://drupal.org/user/581414

This project has been sponsored by:
 * [Farmier](http://farmier.com)

