MopaBootstrapBundle
===================

MopaBootstrapBundle is a collection of code to integrate twitter's bootstrap
(http://twitter.github.com/bootstrap/) as easy as possible into your Symfony2
(http://www.symfony.com) Project.

To use MopaBootstrapBundle and twitters Bootstrap 3 in your project add it via [composer](https://github.com/phiamo/MopaBootstrapBundle/blob/master/Resources/doc/1-installation.md)

Branches
--------

To use this bundle with bootstrap 3 use the latest stable release:

```sh
composer require mopa/bootstrap-bundle twbs/bootstrap
```

To use this bundle with bootstrap SASS with the current master branch:

``` json
{
    "require": {
        "mopa/bootstrap-bundle":    "~3.0.0",
        "twbs/bootstrap":           "v3.2.0"
    }
}
```

If you wish to use the current master branch, then use the following:


```sh
composer require mopa/bootstrap-bundle:dev-master twbs/bootstrap:dev-master
```

For bootstrap 2 use the v2.3.x branch:

```sh
composer require mopa/bootstrap-bundle:2.3.x-dev twbs/bootstrap:2.3.2
```

To understand which versions are currently required have a look into `BRANCHES.md`

Documentation
-------------

The bulk of the documentation is stored in the `Resources/doc/index.md` file in this bundle
In any case, if something is not working as expected after a update:

* [READ the CHANGELOG!](https://github.com/phiamo/MopaBootstrapBundle/blob/master/CHANGELOG.md)


Live Show
---------

To see the bundle, its capabilities, and some more documentation samples just have a look at

[MopaBootstrapBundle Live](http://bootstrap.mohrenweiserpartner.de/mopa/bootstrap)

Additional Resources:

*  [MopaBootstrapSandboxBundle](http://github.com/phiamo/MopaBootstrapSandboxBundle) - Separate live docs from code
*  [symfony-bootstrap](https://github.com/phiamo/symfony-bootstrap) is also available

Installation
------------

Installation instructions are located in the

* [master documentation](https://github.com/phiamo/MopaBootstrapBundle/blob/master/Resources/doc/1-installation.md)

Included Features
-----------------

* Bootstrap Version detection via Composer Bridge
* Twig Extensions and templates for use with Symfony2 Form component
  * control your form either via the form builder or the template engine
  * control nearly every bootstrap2 form feature
  * javascript and twig blocks for dynamic collections
* Knp Menu Extension for dealing with bootstrap menus and navbars.
  * helpers for dropdowns, seperators, etc.
* A tab type for forms to group data
* twig templates for KnpPaginatorBundle (https://github.com/knplabs/KnpPaginatorBundle)
* twig templates for CraueFormFlowBundle (https://github.com/craue/CraueFormFlowBundle)
* twig template for KnpMenuBundle (https://github.com/KnpLabs/KnpMenuBundle)
  * icon support on menu links
* Twig Extension for multiple icon sets

Contribute
----------

If you want to contribute your code to MopaBootstrapBundle please be sure that your PR's
are valid to Symfony Coding Standards. You can automatically fix your code for that
with [PHP-CS-Fixer](http://cs.sensiolabs.org) tool.

Any additional features should include documentation to accompany it.

You can see who already contributed to this project on [Contributors](https://github.com/phiamo/MopaBootstrapBundle/contributors) page

License
-------

This bundle is under the MIT license. For more information, see the complete [LICENCE](LICENCE) file in the bundle.
