# Motivation

Autosetup a virtual infrastructure for testing Flyspray releases and development branches.

# Plan

Write a Vagrantfile that 

* installs and configures Mysql/MariaDB and Postgresql
* installs and configure Apache webserver
* pull Flyspray releases and git branches and installs them
* variation with several ADOdb version and other dependencies
* runs integration test matrix.
* generate a beauty result page with a matrix of versions and test results
