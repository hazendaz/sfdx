# SFDX Compiled Distro #

[![Java CI](https://github.com/hazendaz/sfdx/workflows/Java%20CI/badge.svg)](https://github.com/hazendaz/sfdx/actions?query=workflow%3A%22Java+CI%22)
[![Maven central](https://maven-badges.herokuapp.com/maven-central/com.github.hazendaz.sfdx/sfdx/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.hazendaz.sfdx/sfdx)
[![BSD-3](http://img.shields.io/badge/license-BSD%203-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

![hazendaz](src/site/resources/images/hazendaz-banner.jpg)

This project compiles sfdx for distribution using maven central.

For more information on sfdx, please see [sfdx](https://developer.salesforce.com/developer-centers/developer-experience)

# Motivation #

sfdx does not currently provide a maven central distribution of the project. This project aims to solve that by providing users an alternative location to pull distribution for linux.

This project further provides alternative bundle for windows that does not require an install.

# Use Case #

Maven based storage of distribution in common location to offer more secure download location.

# Windows #

To utilize windows bundle in this, install it to windows from https://developer.salesforce.com/tools/sfdxcli# using 64-bit copy.  The build then points to the expected default windows location of c:\Program Files\sfdx\client

# Retired #

Salesforce has retired SFDX and we have released final version.  See [sfdx retired](https://developer.salesforce.com/blogs/2023/07/salesforce-cli-sf-v2-is-here)

A continuation of this will be against SF(v2) as noted on a new repo in near future.
