# Open-Footprint Plugin

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/) [![GPL Licence](https://badges.frapsoft.com/os/gpl/gpl.svg?v=103)](https://opensource.org/licenses/GPL-3.0/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## About

An open-source platform that monitors the sites you regularly visit, building up a cohesive picture of the information and potential footprint you're placing on the internet.

This project adheres to the Contributor Covenant [code of conduct](CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code. Please report unacceptable behavior to john@johnantoni.com.

## Why

In the past 10 years social media has been increasingly in the focus of the media, with new platforms popping up all the time. It’s addictive and on paper very useful but like most things it has a dark side.

This project aims to give the user a birds-eye view of their journey across the internet super-highway, in order to help teach better internet safety.

## Roadmap

### Browser Plugin (Firefox / Google Chrome)

* Installed via the user.
* Add Name / Alias.
* Reads browser activity, facebook / twitter / etc (can choose how much).
* Checks for facebook / twitter widgets on pages and records it (as if you are logged into facebook each facebook widget you visit connects your browser activity to your facebook account).
* Start building a picture of your activity.
* Show activity on dashboard, like Google Analytics with ability to drill-down to specific points.

## Prerequisites

- git
- node

## Developing

First install the mozilla web-ext command line to to compile the web extension:

    npm install --global web-ext

Next to run the extension move to the src directory:

    cd src/open-footprint

And build with:

    web-ext build

This will generate a zip file in the artifacts directory:

    src/open-footprint/artifacts

From there open Firefox and install the addon from the zipfile.

## Website

- [open-footprint](https://open-footprint.johnantoni.com)

## License

[GNU General Public License v3.0](https://github.com/johnantoni/open-footprint/blob/master/LICENSE.TXT)
