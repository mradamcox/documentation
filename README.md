# ![Islandora 8](https://camo.githubusercontent.com/738dd7cbd90a3ef06b9bb55a4cf5ed385a048fd4/687474703a2f2f69736c616e646f72612e63612f73697465732f64656661756c742f66696c65732f696d616765732f6c6f6273746572434c41572e706e67) Islandora 8

## Introduction

Islandora 8 is the next generation of Islandora. It pairs [Drupal 8](https://www.drupal.org/8) with [Fedora 5](https://wiki.duraspace.org/display/FF/Fedora+Repository+Home)

For more details, please check out the following resources:

* [Weekly Tech Calls](https://github.com/Islandora-CLAW/CLAW/wiki#islandora-claw-tech-calls)
  * [2015](https://github.com/Islandora-CLAW/CLAW/wiki/2015)
  * [2016](https://github.com/Islandora-CLAW/CLAW/wiki/2016)
  * [2017](https://github.com/Islandora-CLAW/CLAW/wiki/2017)
  * [2018](https://github.com/Islandora-CLAW/CLAW/wiki/2018)
  * [2019](https://github.com/Islandora-CLAW/CLAW/wiki/2019)

* [Documentation](https://islandora.github.io/documentation/)
* [Contributing](https://github.com/Islandora-CLAW/CLAW/blob/master/CONTRIBUTING.md)

## Repository Structure

* [Alpaca](https://github.com/islandora-claw/Alpaca): Event driven middleware based on Apache Camel that synchronizes a Fedora with Drupal.
* [docs](https://github.com/Islandora-CLAW/CLAW/tree/master/docs): Documentation!
* [carapace](https://github.com/islandora-claw/carapace/): A starter theme for an Islandora 8 repository. 
* [chullo](https://github.com/islandora-claw/chullo/): PHP client for Fedora 4 built using Guzzle and EasyRdf.
* [claw-playbook](https://github.com/Islandora-Devops/claw-playbook): Ansible installer.
* [controlled_access_terms](https://github.com/islandora-claw/controlled_access_terms/): Drupal module for subjects and agents. 
* [Crayfish](https://github.com/islandora-claw/Crayfish): A collection of Islandora 8 microservices.
* [Crayfish-Commons](https://github.com/Islandora-CLAW/Crayfish-Commons): A library housing shared code for Crayfish microservices
* [drupal-project](https://github.com/Islandora-CLAW/drupal-project): Composer template for Islandora 8 Drupal
* [islandora](https://github.com/Islandora-CLAW/islandora): Islandora 8 Drupal core module
* [islandora_defaults](https://github.com/Islandora-CLAW/islandora_defaults): Starter configuration for an Islandora 8 repository 
* [jsonld](https://github.com/islandora-claw/jsonld): JSON-LD Serializer for Drupal 8
* [migrate_islandora_csv](https://github.com/Islandora-Devops/claw-playbook): Tutorial and example migration into Islandora 8 using a CSV file.
* [migrate_7x_claw](https://github.com/Islandora-Devops/migrate_7x_claw): Starter migration for Islandora 7 -> 8.
* [openseadragon](https://github.com/islandora-claw/openseadragon): Drupal 8 Field Formatter for OpenSeadragon
* [Syn](https://github.com/islandora-claw/Syn): Tomcat valve for JWT Authentication


## Installation
Islandora 8 provides an Ansible [claw-playbook](https://github.com/Islandora-Devops/claw-playbook) to fully deploy the stack to a vagrant, bare-metal server or multi server environments.

## Sponsors

* UPEI
* discoverygarden inc.
* LYRASIS
* McMaster University
* University of Limerick
* York University
* University of Manitoba
* Simon Fraser University
* PALS
* American Philosophical Society
* Common Media Inc.

## Maintainers

* [Daniel Lamb](https://github.com/dannylamb/)
* [Jared Whiklo](https://github.com/whikloj)
* [Diego Pino](https://github.com/DiegoPino)

## Development

If you would like to contribute, please get involved by attending our weekly [Tech Call](https://github.com/Islandora-CLAW/CLAW/wiki). We love to hear from you!

If you would like to contribute code to the project, you need to be covered by an Islandora Foundation [Contributor License Agreement](http://islandora.ca/sites/default/files/islandora_cla.pdf) or [Corporate Contributor Licencse Agreement](http://islandora.ca/sites/default/files/islandora_ccla.pdf). Please see the [Contributors](http://islandora.ca/resources/contributors) pages on Islandora.ca for more information.

We recommend using the [claw-playbook](https://github.com/Islandora-Devops/claw-playbook) to get started.  If you want to pull down the submodules for development, don't forget to run `git submodule update --init --recursive` after cloning.
