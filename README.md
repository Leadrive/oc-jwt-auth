#JWT-Auth plugin

[![Build Status](https://scrutinizer-ci.com/g/gpasztor87/oc-jwt-auth/badges/build.png?b=master)](https://scrutinizer-ci.com/g/gpasztor87/oc-jwt-auth/build-status/master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/gpasztor87/oc-jwt-auth/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/gpasztor87/oc-jwt-auth/?branch=master)
[![StyleCI](https://styleci.io/repos/53659527/shield)](https://styleci.io/repos/53659527)

JSON Web Token Authentication plugin for OctoberCMS.

## Installation

* Extract this repository into plugins/autumn/jwtauth
* In plugins/autumn/api folder run `composer install`.
* Copy the config/jwt.php file to the root config folder.
* Run `php artisan jwt:generate` command.