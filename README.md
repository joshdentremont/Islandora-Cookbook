# Islandora-Cookbook

## Introduction

In the spirit of [Islandora Awesome](https://github.com/Islandora-Labs/islandora_awesome), Islandora Cookbook is a curated list of great modules and other tools for Islandora 8. Because Islandora 8 is more tightly integrated with Drupal, most of these 'recipes' require only Drupal modules as ingredients.

We offer this list for discovery, but do not officially provide support for any of these modules. 

## Table of Contents

  * [Displays](#displays)
  * [Other](#other)

## Islandora 8 Contributed Modules

Warning! - All modules are under development.

* [Islandora RipRap](https://github.com/mjordan/islandora_riprap) - Fixity auditing 
* [Islandora Bagger](https://github.com/mjordan/islandora_bagger) - Utility to generate Bags for objects using Islandora's REST interface using either a command-line tool or via a batch-oriented queue. 
* [Islandora Whole Object](https://github.com/mjordan/islandora_whole_object) - Islandora 8 module that provides some Drupal blocks containing various representations of an Islandora object.
* [Isladnora RDM](https://github.com/roblib/islandora_rdm)


## Contribute

If you would like to contribute to this list, please check out [CONTRIBUTING.md](CONTRIBUTING.md).

If making a new entry, please ensure your pull request adheres to the following guidelines:

* Use the following format:
   * Recipe Title (brief description to the problem solved or feature added) 
     * List of required modules/libraries/software (with live links whereever possible) in the format `[Module Name](link)` 
     * Step-by-step instructions on how to deploy the listed module to accomplish the stated goal. More detail is better but short recipes are accepted as starters.
* Make an individual pull request for each new item.
* Link additions should be inserted alphabetically to the relavant category
* New categories or improvements to the existing categorization are welcome.
* Check your spelling and grammar.
* The pull request and commit should have a useful title.

If updating an existing entry:

* New categories or improvements to the existing categorization are welcome.
* Check your spelling and grammar.
* The pull request and commit should have a useful title.


## Troubleshooting/Issues

Having problems or solved a problem? Check out the Islandora google groups for a solution.

* [Islandora Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora)
* [Islandora Dev Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora-dev)

## Maintainers/Sponsors

Current maintainers:

* [Melissa Anez](https://github.com/manez)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the owner has waived all copyright and related or neighboring rights to this work.

# Recipes

## Access Control

## Displays

## Ingest

## Other

### Batch Editing

[Views Bulk Edit](https://www.drupal.org/project/views_bulk_edit)

A powerful tool that turns Views into a means of batch editing nodes, including Islandora repository objects. Once installled, create a view, add the fields that you would like to edit, add a `Views bulk operations (Edit)` field to the view, and select which actions you would like ot have available. The `Modify field values` action will allow you to batch edit the value for the same field across multiple objects. A demonstration of a simple bulk-editing view with a few fields and actions can be found [here](http://future.islandora.ca/islandora-batch-edit)
