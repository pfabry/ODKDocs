---
layout: ontology_detail
id: ODKDocs
title: ODK test documentation
jobs:
  - id: https://travis-ci.org/pfabry/ODKDocs
    type: travis-ci
build:
  checkout: git clone https://github.com/pfabry/ODKDocs.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: ODK test documentation is an ontology...
domain: stuff
homepage: https://github.com/pfabry/ODKDocs
products:
  - id: ODKDocs.owl
    name: "ODK test documentation main release in OWL format"
  - id: ODKDocs.obo
    name: "ODK test documentation additional release in OBO format"
  - id: ODKDocs.json
    name: "ODK test documentation additional release in OBOJSon format"
  - id: ODKDocs/ODKDocs-base.owl
    name: "ODK test documentation main release in OWL format"
  - id: ODKDocs/ODKDocs-base.obo
    name: "ODK test documentation additional release in OBO format"
  - id: ODKDocs/ODKDocs-base.json
    name: "ODK test documentation additional release in OBOJSon format"
dependencies:
- id: bfo

tracker: https://github.com/pfabry/ODKDocs/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Enter a detailed description of your ontology here. You can use arbitrary markdown and HTML.
You can also embed images too.

