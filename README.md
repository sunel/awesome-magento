Awesome Magento
===============

> A curated list of awesome bookmarks, packages, tutorials, videos and other cool resources from the Magento ecosystem.

Inspired by [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php)

## Table of Contents

- [Essentials](#essentials)
- [Magento Patches](https://github.com/brentwpeterson/magento-patches)
- [Testing](#testing) 
- [Command Line](#command-line)
  - [Magento 1.x](#magento-1x-cli)
  - [Magento 2.x](#magento-2x-cli)
- [Module Manager](#module-manager) 
- [Themes](#themes)
  - [Magento 1.x](#magento-1x-theme)
- [Modules](#modules) 
- [Security](#security)
- [Sessions](#sessions) 
- [Caching](#caching)
  - [Full Page Caching](#full-page-caching)
- [Htaccess](#htaccess)
- [Robot.txt](#robottxt)
- [Nginx](#nginx)
- [MySQL](#mysql)
- [Utils](#utils)
- [Deployments](#deployments)
- [Continuous Integration](#continuous-integration)
- [Composer Integration](#composer-integration)
- [Docker Images](#docker-images)
- [Vagrant Files](#vagrant-files)
- [Sample Data Mirrors](#sample-data-mirrors) 
- [Community Codebases](#community-codebases)
  - [Magento 1.x](#magento-1x-code)
  - [Magento 2.x](#magento-2x-code)
- [Git Ignores](#git-ignores)  
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Books](#books)
  - [Creating Themes](#creating-themes)
  - [Misc](#misc)
- [Contributing](#contributing)

## Contributing
Please see [CONTRIBUTING](https://github.com/sunel/awesome-magento/blob/master/CONTRIBUTING.md) for details.

## Essentials
* [Local Xml](https://github.com/Aproducktion/Magento-local.xml-Template) - A great Start for your Magento Theme's local.xml file

## Testing
* [EcomDev PHPUnit](https://github.com/EcomDev/EcomDev_PHPUnit) - Magento PHPUnit Integration.
* [MageTest BehatMage](https://github.com/MageTest/BehatMage) - Behat for Magento.
* [MageTest MageSpec](https://github.com/MageTest/MageSpec) - PHPSpec for Magento

## Command Line
#### Magento 1.x CLI
* [Mage Run](https://github.com/netz98/n98-magerun) - Tools to work with Magento from command line.
* [Interactive Magento Console](https://github.com/rgranadino/Interactive-Magento-Console)

#### Magento 2.x CLI
* [Mage Run](https://github.com/netz98/n98-magerun2) - Tools to work with Magento from command line.

## Module Manager
* [Modman](https://github.com/colinmollenhour/modman) - Modularize extensions using symlinks.
* [Modgit](https://github.com/jreinke/modgit) - Shell script for Git module deployment with include/exclude filters.

## Themes
#### Magento 1.x theme
  * [Nandroid Foundation](https://github.com/nandroid/MagentoFoundation) - Foundation 3 Framework for Magento.
  * [Webcomm Bootstrap](https://github.com/webcomm/magento-boilerplate) - Bootstrap 3.1 Magento Boilerplate Template.
  * [Cvaldemar Bootstrap](https://github.com/cvaldemar/magento-bootstrap) - Another Bootstrap based Magento Template.
  * [Pendabl Bootstrap](https://github.com/pendabl/bootstrapped) - Another Bootstrap based Magento Template.
  * [Zeljkoprsa Boilerplate](https://github.com/zeljkoprsa/Magento-Boilerplate) - Magento Theme Package based on HTML5 Bolierplate.
  * [Gpmd Responsive Theme](https://github.com/gpmd/magento-responsive-theme) - Simple responsive (fluid) Magento theme.
  * [Jreinke Admin Theme](https://github.com/jreinke/magento-admin-theme) - Magento Admin a facelift.

## Modules
#### Magento 1.x modules
  * [VF EasyAjax](https://github.com/hws47a/VF_EasyAjax) - Send ajax requests and return a custom information from the server.
  * [FastIndexer](https://github.com/SchumacherFM/Magento-FastIndexer) - Makes indexing of your Magento store around x times faster!.
  * [Strategery-Inc/Magento-InfiniteScroll](https://github.com/Strategery-Inc/Magento-InfiniteScroll) - Automatically load the next page of products in Magento.
  * [Switcher](https://github.com/tzyganu/Switcher) - Configurable products switcher extension that allows you to change the configurable products dropdowns to labels, colors or images.
  * [UMC1.9](https://github.com/tzyganu/UMC1.9) - New Ultimate Module Creator for Magento 1.7 +.
  * [Simple Configurable Products](https://github.com/organicinternet/magento-configurable-simple) - Enhancement to Magento to allow simple product prices to be used instead of the default special-case configurable product prices.
  * [Customer Activation](https://github.com/Vinai/customer-activation) - Magento extension which makes it impossible for a customer to log in until the account has been activated by the administrator.
  * [Magento layered navigation](https://github.com/caciobanu/improved-magento-layered-navigation) - Improved Magento layered navigation extension.
  * [Magento ElasticSearch](https://github.com/Smile-SA/smile-magento-elasticsearch) - Magento ElasticSearch Implementation.

#### Magento 2.x modules
  * [Magento ElasticSearch](https://github.com/Smile-SA/elasticsuite) - Magento ElasticSearch Implementation.

## Security
* [MageFirewall](https://github.com/paimpozhil/MageFirewall) - Magento Firewall for securing your e-commerce system.

## Sessions
* [Cm RedisSession](https://github.com/colinmollenhour/Cm_RedisSession) - Redis-based session handler for Magento with optimistic locking.

## Caching
* [Guidance Cachebuster](https://github.com/gordonknoppe/magento-cachebuster) - Automatic purging of static assets from HTTP caches.
* [Cm_Cache_Backend_Redis](https://github.com/colinmollenhour/Cm_Cache_Backend_Redis) - A Zend_Cache backend for Redis with full support for tags.
* [Cm_Cache_Backend_File](https://github.com/colinmollenhour/Cm_Cache_Backend_File) - Much improved replacement for Zend_Cache_Backend_File.
* [Zend_Cache_Backend_Mongo](https://github.com/AntonStoeckl/Zend_Cache_Backend_Mongo) - Zend Framework cache backend for MongoDB.

### Full Page Caching
  * [Nexcess Turpentine](https://github.com/nexcess/magento-turpentine) - Cache extension for Magento that works with Varnish.
  * [Betabrand Varnish](https://github.com/huguesalary/Magento-Varnish) - Another Cache extension for Magento that works with Varnish.
  * [Lesti Fpc](https://github.com/GordonLesti/Lesti_Fpc) - Simple Magento Fullpagecache.

## Htaccess
* [Magento Htaccess](https://github.com/Creare/magento-htaccess) - A htaccess boilerplate for all Magento Community installations.

## Robot.txt
* [Robot.txt](https://github.com/Creare/magento-robots) - A simple SEO robots.txt boilerplate for all Magento Community installations.

## Nginx
* [Magento Nginx](https://github.com/magenx/nginx-config) - Default Nginx config for Magento.

## MySQL
* [Magento MySQL](https://github.com/magenx/magento-mysql) - Magento default mysql settings.

## Utils
* [Magento Utils](https://github.com/akira28/magento-utils) - A collection of snippets and scripts to simplify your life as a Magento developer.
* [Coding Standard](https://github.com/magento-ecg/coding-standard) - Magento Code Sniffer Coding Standard.
* [PHPCS Rules](https://github.com/madedotcom/phpcs-magento-rules) - PHPCS Magento Rules
* [Magento Tools](https://github.com/jmmastey/magento-tools) - Tools to help work with Magento.
* [MagentoSnippets for Sublime](https://github.com/MageFront/MagentoSnippets) - Magento Front End Snippets, plugin for Sublime Text.

## Deployments
* [Cookbook Magento](https://github.com/yevgenko/cookbook-magento) - Collection of recipes to build app stack for the Magento deployments with Chef.
* [Chef Magento](https://github.com/inviqa/chef-magento) - Installs and Configures a Magento project with Chef.
* [Deploy Scripts](https://github.com/AOEpeople/magento-deployscripts) - Scripts used to build/package, deploy and install Magento projects.
* [MASC-M](https://github.com/magenx/MASC-M) - Automated Server Configuration for Magento.

## Continuous Integration
* [EcomDev MageCI](https://github.com/EcomDev/MageCI) - A set of tools to help set up a proper environment for testing magento.

## Composer Integration
* [Cotya Composer](https://github.com/Cotya/magento-composer-installer) - Composer installer for Magento modules.

## Docker Images
* [Docker Magento](https://github.com/alexcheng1982/docker-magento) - Docker image for Magento.
* [Docker Magento](https://github.com/kojiromike/docker-magento) - Another Docker image for Magento.
* [Magento Nginx](https://github.com/dockerfiles/magento-nginx) - Docker Container Template for Magento with NginX and php-fpm.
* [Docker Magento](https://github.com/paimpozhil/docker-magento) - Production ready scalable Magento setup utilizing the docker.

## Vagrant Files
* [Magento Vagrant Puppet](https://github.com/cmuench/Magento-Vagrant-Puppet) - A Vagrantfile and some puppet scripts for an installation of a magento shop.
* [Magento Vagrant Puppet Nginx](https://github.com/cmuench/Magento-Vagrant-Puppet-Nginx) - Installs magento and a nginx server.
* [Jasonevans1 Vagrant](https://github.com/jasonevans1/vagrant-magento) - Another Vagrant project for Magento
* [Amacgregor MageVagrant](https://github.com/amacgregor/MageVagrant) - Vagrant/Chef base box for running Magento.

## Sample Data Mirrors
* [Sample Data Compressed](https://github.com/Vinai/compressed-magento-sample-data) - A highly compressed version of the magento 1.9 sample data and a script to create it.
* [Sample Data](http://mirror.gunah.eu/magento/sample-data/) - Another mirrir link

## Community Codebases
#### Magento 1.x Code
  * [Firegento](https://github.com/firegento/magento) (unofficial)
  * [OpenMage](https://github.com/OpenMage/magento-lts) (unofficial)
  * [Bragento](https://github.com/bragento/magento-core) (unofficial)

#### Magento 2.x Code 
  * [Magento](https://github.com/magento/magento2) (official)

## Git Ignores
* [Magento Gitignore](https://github.com/webcomm/magento-gitignore) - .gitignore file for Magento-based projects.
* [Magento Gitignore](https://github.com/github/gitignore/blob/master/Magento.gitignore) - Another .gitignore file for Magento-based projects.
* [Inchoo Gitignore](http://inchoo.net/magento/programming-magento/git-ignore-gitignore-file-for-magento-project/) - Another .gitignore file for Magento-based projects by inchoo.

## Resources
* [Magento-Functions](https://github.com/Aproducktion/Magento-Functions) - A Resource of Magento Functions.


#### Blogs
  * [Inchoo](http://inchoo.net/magento/)
  * [Belvg](http://blog.belvg.com/tag/magento-certification)
  * [Demac Media](http://www.demacmedia.com/category/magento-commerce/)
  * [Nick Says](https://www.nicksays.co.uk/magento/)
  * [Fabrizio Banca](http://fbrnc.net/blog/tag:Magento)
  * [Magento Quickies](http://magento-quickies.alanstorm.com/)
  * [Alan Storm](http://alanstorm.com/category/magento)

#### Books
  * [Magento for Developers Guide](http://www.magentocommerce.com/knowledge-base/entry/magento-for-dev-part-1-introduction-to-magento)
  * [Magento Best Practices](http://www.nexcess.net/resources/white-papers/magento-best-practices)
  * [Magento PHP Developer's Guide](http://magedevguide.com/)

#### Creating Themes
  * [Magento Themes from scratch](http://magento.stackexchange.com/questions/3780/theming-starting-from-scratch)
  * [Introducing Magento Layout](http://www.smashingmagazine.com/2012/11/30/introducing-magento-layout/)
  * [Magento local.xml Boilerplate](http://www.creare.co.uk/magento-local-xml-boilerplate)

#### Become Certified
  * [Magento Certified Developer study guide](http://magestudyguide.com/)
  * [Moderators Kit](http://magento.com/training/catalog/moderators-kit)
  * [Magecert](http://magecert.com/)

####  For Users / Store administrators
  * [Magento User Guides](http://www.magentocommerce.com/resources/magento-user-guide)

#### Misc
  * [Magento Developers List](http://magehero.com/)
  * [Magento on Stackexchange](http://magento.stackexchange.com)
  * [Magento on Stackoverflow](http://stackoverflow.com/questions/tagged/magento)
  * [Magento on Reddit](http://www.reddit.com/r/magento)
  * [Magento The Right Way](https://magentotherightway.com/)
