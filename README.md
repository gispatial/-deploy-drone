# Deploy Drone CI by Rizq Solutions DevOps Elite
[![Stack](https://raw.githubusercontent.com/paralect/stack/master/stack-component-template/stack.png)](https://github.com/paralect/stack)

[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![Watch on GitHub](https://img.shields.io/github/watchers/paralect/docker-compose-starter.svg?style=social&label=Watch)](https://github.com/paralect/deploy-drone/watchers)
[![Star on GitHub](https://img.shields.io/github/stars/paralect/deploy-drone.svg?style=social&label=Stars)](https://github.com/paralect/deploy-drone/stargazers)
[![Follow](https://img.shields.io/twitter/follow/paralect.svg?style=social&label=Follow)](https://twitter.com/paralect)
[![Tweet](https://img.shields.io/twitter/url/https/github.com/paralect/deploy-drone.svg?style=social)](https://twitter.com/intent/tweet?text=Deploy%20Drone%20CI%20to%20enable%20continuous%20integration%20on%20your%20product%20via%20https://github.com/paralect/deploy-drone)

[Drone](https://drone.io/) is free and open-source continuous delivery platform that automates your testing and release workflow. It is lightweight, stupidly simple, free & [Docker](https://www.docker.com/) based. 
When we first met with Drone, it took us few days to adopt it for our products, play around and deploy to production. This repository aims to save your time from few days to few hours to get started. Last year we also written [a blog post](https://blog.maqpie.com/2017/03/21/build-and-deploy-applications-using-drone-ci-docker-and-ansible/) about some details of our CI process. Please, be aware that blog post was written for version 0.5, while current version is 0.8.6 and few things have changed.

## Features

* 👌 **Local setup** with a single command. 
* ️⚡️️ **Production deployment** automation behind [Nginx](https://nginx.org/en/) proxy with optional SSL support.

## Getting Started

1. [Setup github oauth application](OAUTH_APP.md) — this is required for both local and production environments.
2. [Setup Drone on local machine](local/README.md). This is a good way to get started with drone.
3. [Deploy to production](SETUP.md). 

## Demo

A real word Drone usage example is available [here](https://github.com/paralect/ship/blob/master/.drone.yml).

## Change Log

This project adheres to [Semantic Versioning](http://semver.org/).
Every release is documented on the Github [Releases](https://github.com/paralect/deploy-drone/releases) page.

## License

Deploy Drone is released under the [MIT License](LICENSE).

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/anorsich"><img src="https://avatars3.githubusercontent.com/u/681396?v=4" width="100px;" alt="Andrew Orsich"/><br /><sub><b>Andrew Orsich</b></sub></a><br /><a href="#question-anorsich" title="Answering Questions">💬</a> <a href="#blog-anorsich" title="Blogposts">📝</a> <a href="https://github.com/auxilin/deploy-drone/commits?author=anorsich" title="Code">💻</a> <a href="#ideas-anorsich" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/anorsich"><img src="https://avatars3.githubusercontent.com/u/681396?v=4" width="100px;" alt="Andrew Orsich"/><br /><sub><b>Andrew Orsich</b></sub></a><br /><a href="#question-anorsich" title="Answering Questions">💬</a> <a href="#blog-anorsich" title="Blogposts">📝</a> <a href="https://github.com/auxilin/deploy-drone/commits?author=anorsich" title="Code">💻</a> <a href="#ideas-anorsich" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/ezhivitsa"><img src="https://avatars2.githubusercontent.com/u/6461311?v=4" width="100px;" alt="Evgeny Zhivitsa"/><br /><sub><b>Evgeny Zhivitsa</b></sub></a><br /><a href="https://github.com/auxilin/deploy-drone/commits?author=ezhivitsa" title="Code">💻</a> <a href="#ideas-ezhivitsa" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/IharKrasnik"><img src="https://avatars3.githubusercontent.com/u/2302873?v=4" width="100px;" alt="Ihar"/><br /><sub><b>Ihar</b></sub></a><br /><a href="https://github.com/auxilin/deploy-drone/commits?author=IharKrasnik" title="Code">💻</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!
