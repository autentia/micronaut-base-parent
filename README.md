# Micronaut Maven base parent

The purpose of this module is to easily add [Micronaut](https://micronaut.io/) support to your Maven projects. 

This module define some Maven properties with typical values or package versions, but you can override this properties in your project `pom.xml` to change the default behaviour.

In this module you can find the configuration of some typical Maven plugins thar are used with Micronaut. Please refer to the `pom.xml` of this module to see these configurations.
 
This is a Maven base module just to define some common defaults, so is preferred that you don not use it directly and instead in your project you should use one of:
 
 - [micronaut-java-parent](https://github.com/autentia/micronaut-java-parent)
 - [micronaut-kotlin-parent](https://github.com/autentia/micronaut-kotlin-parent)
 