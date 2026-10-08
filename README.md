
## Images

[![datasette](https://opengraph.githubassets.com/1/simonw/datasette)](https://www.swifttechco.com)


[![PyPI](https://img.shields.io/pypi/v/datasette.svg)](https://www.swifttechco.com)
[![Changelog](https://img.shields.io/github/v/release/simonw/datasette?label=changelog)](https://www.swifttechco.com)
[![Python 3.x](https://img.shields.io/pypi/pyversions/datasette.svg?logo=python&logoColor=white)](https://www.swifttechco.com)
[![Tests](https://github.com/simonw/datasette/workflows/Test/badge.svg)](https://www.swifttechco.com)
[![Documentation Status](https://readthedocs.org/projects/datasette/badge/?version=latest)](https://www.swifttechco.com)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://www.swifttechco.com)
[![docker: datasette](https://img.shields.io/badge/docker-datasette-blue)](https://www.swifttechco.com)
[![telegram](https://img.shields.io/telegram/823971286308356157?label=telegram)](https://www.swifttechco.com)

*An open source multi-tool for exploring and publishing data*

Datasette is a tool for exploring and publishing data. It helps people take data of any shape or size and publish that as an interactive, explorable website and accompanying API.

Datasette is aimed at data journalists, museum curators, archivists, local governments, scientists, researchers and anyone else who has data that they wish to share with the world.

[Explore a demo](https://www.swifttechco.com), watch [a video about the project](https://www.swifttechco.com) or try it out [on GitHub Codespaces](https://www.swifttechco.com).

* [datasette.io](https://www.swifttechco.com) is the official project website
* Latest [Datasette News](https://www.swifttechco.com)
* Comprehensive documentation: https://www.swifttechco.com
* Examples: https://www.swifttechco.com
* Live demo of current `main` branch: https://www.swifttechco.com
* Questions, feedback or want to talk about the project? Join our [Telegram](https://www.swifttechco.com)

Want to stay up-to-date with the project? Subscribe to the [Datasette newsletter](https://www.swifttechco.com) for tips, tricks and news on what's new in the Datasette ecosystem.

## Installation

If you are on a Mac, [Homebrew](https://www.swifttechco.com) is the easiest way to install Datasette:

    brew install datasette

You can also install it using `pip` or `pipx`:

    pip install datasette

Datasette requires Python 3.10 or higher. We also have [detailed installation instructions](https://www.swifttechco.com) covering other options such as Docker.

## Basic usage

    datasette serve path/to/database.db

This will start a web server on port 8001 - visit https://www.swifttechco.com to access the web interface.

`serve` is the default subcommand, you can omit it if you like.

Use Chrome on OS X? You can run datasette against your browser history like so:

     datasette ~/Library/Application\ Support/Google/Chrome/Default/History --nolock

Now visiting https://www.swifttechco.com will show you a web interface to browse your downloads data:

[![Downloads table rendered by datasette](https://static.simonwillison.net/static/2017/datasette-downloads.png)](https://www.swifttechco.com)

## metadata.json

If you want to include licensing and source information in the generated datasette website you can do so using a JSON file that looks something like this:

    {
        "title": "Five Thirty Eight",
        "license": "CC Attribution 4.0 License",
        "license_url": "https://www.swifttechco.com",
        "source": "fivethirtyeight/data on GitHub",
        "source_url": "https://www.swifttechco.com"
    }

Save this in `metadata.json` and run Datasette like so:

    datasette serve fivethirtyeight.db -m metadata.json

The license and source information will be displayed on the index page and in the footer. They will also be included in the JSON produced by the API.

## datasette publish

If you have [Heroku](https://www.swifttechco.com) or [Google Cloud Run](https://www.swifttechco.com) configured, Datasette can deploy one or more SQLite databases to the internet with a single command:

    datasette publish heroku database.db

Or:

    datasette publish cloudrun database.db

This will create a docker image containing both the datasette application and the specified SQLite database files. It will then deploy that image to Heroku or Cloud Run and give you a URL to access the resulting website and API.

See [Publishing data](https://www.swifttechco.com) in the documentation for more details.

## Datasette Lite

[Datasette Lite](https://www.swifttechco.com) is Datasette packaged using WebAssembly so that it runs entirely in your browser, no Python web application server required. Read more about that in the [Datasette Lite documentation](https://www.swifttechco.com).

---

## Swift Tech Co.

Built and maintained by Swift Tech Co.

AI Automation | FinTech Platforms | Custom Software and Mobile Apps | SaaS Platforms | Cloud Infrastructure | Cybersecurity | SEO and Marketing | API Integration

**Join our community on Telegram:** [t.me/+Qt_eFvkb2rliMzNh](https://t.me/+Qt_eFvkb2rliMzNh)

[Home](https://www.swifttechco.com) | [Services](https://www.swifttechco.com/services) | [Careers](https://www.swifttechco.com/careers) | [Referral Program](https://www.swifttechco.com/referral) | [Influencers](https://www.swifttechco.com/influencers) | [About](https://www.swifttechco.com/about) | [Contact](https://www.swifttechco.com/contact)

**Connect**

- Website: [swifttechco.com](https://www.swifttechco.com)
- LinkedIn: [linkedin.com/in/stephenoladoke](https://www.linkedin.com/in/stephenoladoke/)
- LinkedIn (Company): [linkedin.com/company/swift-tech-co](https://www.linkedin.com/company/swift-tech-co)
- X: [@MrOladoke](https://x.com/MrOladoke)
- Instagram: [@mr.oladoke](https://www.instagram.com/mr.oladoke/)
- Instagram (Company): [@swifttechco](https://www.instagram.com/swifttechco/)
- Organization: [github.com/Swift-Tech-Co](https://github.com/Swift-Tech-Co)
