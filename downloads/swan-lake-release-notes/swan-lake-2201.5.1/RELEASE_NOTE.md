---
layout: ballerina-left-nav-release-notes
title: 2201.5.1 (Swan Lake) 
permalink: /downloads/swan-lake-release-notes/2201-5-1/
active: 2201-5-1
---

## Overview of Ballerina Swan Lake 2201.5.1

<em>Swan Lake 2201.5.1 is the first patch release of Ballerina 2201.5.0 (Swan Lake Update 5) and it includes a new set of bug fixes to the language and tooling.</em>

## Update Ballerina

Update your current Ballerina installation directly to 2201.5.1 using the [Ballerina Update Tool](/learn/update-tool/) as follows.

1. Run `bal update` to get the latest version of the Update Tool.
2. Run `bal dist pull 2201.5.1` to update to this latest distribution.

## Install Ballerina

If you have not installed Ballerina, then, download the [installers](/downloads/#swanlake) to install.

## Language updates

### Bug fixes

To view bug fixes, see the [GitHub milestone for 2201.5.1 (Swan Lake)](https://github.com/ballerina-platform/ballerina-lang/issues?q=is%3Aissue+milestone%3A2201.5.1+label%3AType%2FBug+is%3Aclosed).

## Developer tools updates

### Improvements

#### OpenAPI Tool
- Added support for object-typed query parameters in the OpenAPI to Ballerina service generation.
- Added support to generate low-level service skeletons without any data-binding logic. This mode can be enabled by adding the `--without-data-binding` flag to the OpenAPI to Ballerina service generation command.
