# ArmorJS - Project Guide

## Projects


Action Result
![CI](https://github.com/armorjs/action-result/workflows/CI/badge.svg?branch=master) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=armorjs_action-result&metric=coverage)](https://sonarcloud.io/dashboard?id=armorjs_action-result) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=armorjs_action-result&metric=alert_status)](https://sonarcloud.io/dashboard?id=armorjs_action-result)
-----
### Standard interface for result and status for action calls. 


Build
![CI](https://github.com/armorjs/build/workflows/CI/badge.svg?branch=master) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=armorjs_build&metric=coverage)](https://sonarcloud.io/dashboard?id=armorjs_build) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=armorjs_build&metric=alert_status)](https://sonarcloud.io/dashboard?id=armorjs_build) 
-----

### Suite of common build functions used in gulp builds.
[![npm link](https://raw.githubusercontent.com/armorjs/_project-home/master/assets/images/npm.png =64x)](https://www.npmjs.com/package/@armorjs/build) [![github](https://raw.githubusercontent.com/armorjs/_project-home/master/assets/images/github.png =64x)](https://github.com/armorjs/build)



Key Store
![CI](https://github.com/armorjs/key/workflows/CI/badge.svg?branch=master) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=armorjs_key-store&metric=coverage)](https://sonarcloud.io/dashboard?id=armorjs_key-store) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=armorjs_key-store&metric=alert_status)](https://sonarcloud.io/dashboard?id=armorjs_key-store)
-----


Headless
![CI](https://github.com/armorjs/headless/workflows/CI/badge.svg?branch=master) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=armorjs_headless&metric=coverage)](https://sonarcloud.io/dashboard?id=armorjs_headless) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=armorjs_headless&metric=alert_status)](https://sonarcloud.io/dashboard?id=armorjs_headless)
-----
### Headless browser for automated testing.


## Mission

### Challenges
Node's diverse package ecosystem and rapidly evolving features are strengths that also create challenges for enterprise use. Typical node projects have 1000s of dependencies which change frequently. The [2016 left-pad fiasco](https://arstechnica.com/information-technology/2016/03/rage-quit-coder-unpublished-17-lines-of-javascript-and-broke-the-internet/) and [2018 dependency trolling](https://medium.com/hackernoon/im-harvesting-credit-card-numbers-and-passwords-from-your-site-here-s-how-9a8cb347c5b5) highlight the difficulty of auditing npm dependencies for code, license, and security issues.

### Solutions
ArmorJS 


* Reliability
	* Thorough testing
	* Strict Static analysis
	* Consistent code reviews
* Consistency
	* Features deprecated with warning long before removal.
	* Slow and gradual API changes over time
* Small Footprint
	* Small number of external non-dev dependencies per project (most have 0).
	* Tiny bundled size is ideal webpacking or serverless uses.

## Contributions

ArmorJS packages are focused on reliability, consistency, and small footprint for enterprise audiences. Pull requests are absolutely welcomed. Strong communities make better software. 

## License
ArmorJS projects are MIT licensed.