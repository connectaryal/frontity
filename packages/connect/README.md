# `@frontity/connect`

[![Version](https://img.shields.io/npm/v/@frontity/connect.svg)](https://www.npmjs.com/package/@frontity/connect) [![npm](https://img.shields.io/npm/dw/@frontity/connect)](https://www.npmjs.com/package/@frontity/connect) [![License: Apache--2.0](https://img.shields.io/badge/license-Apache%202-lightgrey)](https://github.com/frontity/frontity/blob/master/LICENSE)

The state manager of Frontity.  
Similar to [MobX](https://mobx.js.org/README.html) but much more lightweight because it's based on [ES6 proxies](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy).

## Table of contents

<!-- toc -->

- [Install](#install)
- [Usage](#usage)
- [Feature Discussions](#feature-discussions)
- [Changelog](#changelog)
- [Open Source Community](#open-source-community)
  * [Channels](#channels)
  * [Get involved](#get-involved)

<!-- tocstop -->

## Install

This package is not meant to be installed individually.  
The public methods defined in `@frontity/connect` are meant to be used through [`frontity`](https://github.com/frontity/frontity/tree/dev/packages/frontity) package (from which we can import these [methods](https://github.com/frontity/frontity/blob/dev/packages/frontity/src/index.ts)).

## Usage

Some interesting methods defined in this package and available through [`frontity`](https://github.com/frontity/frontity/tree/dev/packages/frontity) package are:

- [`connect`](https://docs.frontity.org/api-reference-1/frontity#connect)
- [`useConnect`](https://docs.frontity.org/api-reference-1/frontity#useconnect)

## Feature Discussions

[**Feature Discussions**](https://community.frontity.org/c/feature-discussions/33) about Frontity are public. You can join the discussions, vote for those you're interested in or create new ones.

These are the ones related to this package: https://community.frontity.org/tags/c/feature-discussions/33/connect

## Changelog

Have a look at the latest updates of this package in the [CHANGELOG](https://github.com/frontity/frontity/blob/dev/packages/connect/CHANGELOG.md)

***

## Open Source Community

### Channels

[![Community Forum Topics](https://img.shields.io/discourse/topics?color=blue&label=community%20forum&server=https%3A%2F%2Fcommunity.frontity.org%2F)](https://community.frontity.org/) [![Twitter: frontity](https://img.shields.io/twitter/follow/frontity.svg?style=social)](https://twitter.com/frontity) ![Frontity Github Stars](https://img.shields.io/github/stars/frontity/frontity?style=social)

Frontity has a number of different channels at your disposal where you can find out more information about the project, join in discussions about it, and also get involved:

- **📖  [Docs](https://docs.frontity.org/):** Frontity's primary documentation resource - this is the place to learn how to build amazing sites with Frontity.
* **👨‍👩‍👧‍👦  [Community forum](https://community.frontity.org/):** join Frontity's forum and ask questions, share your knowledge, give feedback and meet other cool Frontity people. We'd love to know about what you're building with Frontity, so please do swing by the [forum](https://community.frontity.org/) and tell us about your projects.
* **🐞  Contribute:** Frontity uses [GitHub](https://github.com/frontity/frontity) for bugs and pull requests. Check out the [Contributing](../contributing/) section to find out how you can help develop Frontity, or improve this documentation.
* **🗣  Social media**: interact with other Frontity users. Reach out to the Frontity team on [Twitter](https://twitter.com/frontity). Mention us in your tweets about Frontity and what you're building by using **`@frontity`**.
* 💌  **Newsletter:** do you want to receive the latest news about Frontity and find out as soon as there's an update to the framework? Subscribe to our [newsletter](https://frontity.org/#newsletter).

### Get involved

[![GitHub issues by-label](https://img.shields.io/github/issues/frontity/frontity/good%20first%20issue)](https://github.com/frontity/frontity/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)

Got questions or feedback about Frontity? We'd love to hear from you in our [community forum](https://community.frontity.org).

Frontity also welcomes contributions. There are many ways to support the project! If you don't know where to start then this guide might help: [How to contribute?](https://docs.frontity.org/contributing/how-to-contribute).

If you would like to start contributing to the code please open a pull request to address one of our [*good first issues*](https://github.com/frontity/frontity/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).