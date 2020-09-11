<a name="README">[<img src="https://rawgithub.com/jasmine/jasmine/main/images/jasmine-horizontal.svg" width="400px" />](http://jasmine.github.io)</a>

[![Build Status](https://circleci.com/gh/jasmine/jasmine.svg?style=shield)](https://circleci.com/gh/jasmine/jasmine)
[![Open Source Helpers](https://www.codetriage.com/jasmine/jasmine/badges/users.svg)](https://www.codetriage.com/jasmine/jasmine)

# A JavaScript Testing Framework

Jasmine is a Behavior Driven Development testing framework for JavaScript. It does not rely on browsers, DOM, or any JavaScript framework. Thus it's suited for websites, [Node.js](http://nodejs.org) projects, or anywhere that JavaScript can run.

Upgrading from Jasmine 3.x? Check out the [upgrade guide](https://jasmine.github.io/tutorials/upgrading_to_Jasmine_4.0).

## Contributing

Please read the [contributors' guide](https://github.com/jasmine/jasmine/blob/main/.github/CONTRIBUTING.md).

## Why the fork?

For ElectronJS versions 11.0.0-nightly.20200721 and beyond, [karma-electron-launcher](https://github.com/lele85/karma-electron-launcher) is able to capture ElectronJS but no tests get run.  This fork [patches](https://github.com/v-kpheng/jasmine/blob/electron-missing-jasmineFile/src/core/util.js#L119) the issue.

The last nightly build that karma-electron-launcher was able to run tests against was 11.0.0-nightly.20200720.  The diff between that version and 11.0.0-nightly.20200721 is: https://github.com/electron/electron/compare/8f5280a821644a57e1f041a1bf570035d48cd4f6...95dd81bd689416fe02efad77c973a5643ab88a54.

## Why the fork?

For ElectronJS versions 11.0.0-nightly.20200721 and beyond, [https://github.com/lele85/karma-electron-launcher](karma-electron-launcher) is able to capture ElectronJS but no tests get run.  This fork [https://github.com/v-kpheng/jasmine/blob/electron-missing-jasmineFile/src/core/util.js#L119](patches) the issue.

The last nightly build that karma-electron-launcher was able to run tests against was 11.0.0-nightly.20200720.  The diff between that version and 11.0.0-nightly.20200721 is: https://github.com/electron/electron/compare/8f5280a821644a57e1f041a1bf570035d48cd4f6...95dd81bd689416fe02efad77c973a5643ab88a54.

## Installation

There are several different ways to install Jasmine, depending on your 
environment and how you'd like to use it. See the [Getting Started page](https://jasmine.github.io/pages/getting_started.html)
for details.

## Usage

See the [documentation site](https://jasmine.github.io/pages/docs_home.html),
particularly the [Your First Suite tutorial](https://jasmine.github.io/tutorials/your_first_suite)
for information on writing specs, and [the FAQ](https://jasmine.github.io/pages/faq.html).

## Supported environments

Jasmine tests itself across popular browsers (Safari, Chrome, Firefox, and
Microsoft Edge) as well as Node.

| Environment       | Supported versions |
|-------------------|--------------------|
| Node              | 12.17+, 14, 16, 18 |
| Safari            | 14-15              |
| Chrome            | Evergreen          |
| Firefox           | Evergreen, 91      |
| Edge              | Evergreen          |

For evergreen browsers, each version of Jasmine is tested against the version of the browser that is available to us
at the time of release. Other browsers, as well as older & newer versions of some supported browsers, are likely to work.
However, Jasmine isn't tested against them and they aren't actively supported. 

To find out what environments work with a particular Jasmine release, see the [release notes](https://github.com/jasmine/jasmine/tree/main/release_notes).

## Maintainers

* [Gwendolyn Van Hove](mailto:gwen@slackersoft.net)
* [Steve Gravrock](mailto:sdg@panix.com)

### Maintainers Emeritus

* [Davis W. Frank](mailto:dwfrank@pivotal.io)
* [Rajan Agaskar](mailto:rajan@pivotal.io)
* [Greg Cobb](mailto:gcobb@pivotal.io)
* [Chris Amavisca](mailto:camavisca@pivotal.io)
* [Christian Williams](mailto:antixian666@gmail.com)
* Sheel Choksi

Copyright (c) 2008-2022 Jasmine Maintainers. This software is licensed under the [MIT License](https://github.com/jasmine/jasmine/blob/main/MIT.LICENSE).
