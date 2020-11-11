# Tugboat configuration files for Drupal.org

This repository contains a set of .tugboat/config.yml files to support
different versions of Drupal core at Drupal.org.

## How it works

When a merge request is created against Drupal core, Drupal.org looks at either a matching branch at https://github.com/TugboatQA/drupalorg/tree/master/drupal or otherwise picks the [default configuration](https://github.com/TugboatQA/drupalorg/tree/master/drupal).

Each configuration file defines the set of commands to build the environment. Have a look at the default configuration file (used by Drupal 9 and some branches of Drupal 8) at https://github.com/TugboatQA/drupalorg/blob/master/drupal/default/config.yml.

## Contributing

This is a public repository so if you find a bug or want to contribute a new feature, create and issue and/or a pull request.
