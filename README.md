# Connector
This repository is a part of proposal of main app modulariaztion.

Connector serves as a gradle project which gathers all artifacts produced by all modules of application.
It doesn't have any code, only gradle files, where dependencies are defined.
Besides module dependency, all 3-rd party dependencies should also be defined here.

Another function of Connector: it can be linked as git submodule to feature repository and help to build each feature independently.
See [Dashboard repository](https://github.com/andrii-lytvyniuk-ring/Dashboard).

## master branch
*master* branch is intended to be a source of application release. It contains only dependencies on artifacts.

## feature_bundle branch
*feature_bundle* is alternative way to build application. This version allows to build feature bundle.
Rest is the same as in *master*
