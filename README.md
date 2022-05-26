<h1 align="center">
  <a href="https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper">
    <!-- Please provide path to your logo here -->
    <img src="docs/images/logo.svg" alt="Logo" width="100" height="100">
  </a>
</h1>

<div align="center">
  MAPS-Great-Streets-Survey-ykimdeveloper
  <br />
  <a href="#about"><strong>Explore the screenshots »</strong></a>
  <br />
  <br />
  <a href="https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper/issues/new?assignees=&labels=bug&template=01_BUG_REPORT.md&title=bug%3A+">Report a Bug</a>
  ·
  <a href="https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper/issues/new?assignees=&labels=enhancement&template=02_FEATURE_REQUEST.md&title=feat%3A+">Request a Feature</a>
  .
  <a href="https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper/issues/new?assignees=&labels=question&template=04_SUPPORT_QUESTION.md&title=support%3A+">Ask a Question</a>
</div>

<div align="center">
<br />

[![Project license](https://img.shields.io/github/license/ykimdeveloper/maps-great-streets-survey-ykimdeveloper.svg?style=flat-square)](LICENSE)

[![Pull Requests welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg?style=flat-square)](https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)
[![code with love by ykimdeveloper](https://img.shields.io/badge/%3C%2F%3E%20with%20%E2%99%A5%20by-ykimdeveloper-ff1414.svg?style=flat-square)](https://github.com/ykimdeveloper)

</div>

<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Support](#support)
- [Project assistance](#project-assistance)
- [Contributing](#contributing)
- [Authors & contributors](#authors--contributors)
- [Security](#security)
- [License](#license)
- [Acknowledgements](#acknowledgements)

</details>

---

## About

> This is a continuation of the data analysis project using L.A. city's data 'Great Streets Pedestrian Survey 2015'.  
> The data shown is already data wrangled and cleaned which is described on my other repo.
> This project is to demonstrate how to use SQL data with python.


<details>
<summary>Screenshots</summary>
<br>


|                               GEOMETRIC_CENTER                               |                               APPROXIMATE                              |
| :-------------------------------------------------------------------: | :--------------------------------------------------------------------: |
| <img src="docs/images/geometric_center.png" title="Home Page" width="100%"> | <img src="docs/images/approx.png" title="Login Page" width="100%"> |

</details>

### Built With

*  requests module
*  json module for google maps api
*  urllib

## Getting Started

### Prerequisites

* pip install request
* pip install json
* pip install urllib
* pip install folium

### Installation

* get google maps API key before starting
## Usage


```python
base_url= "https://maps.googleapis.com/maps/api/geocode/json?"
AUTH_KEY = ""

# set up your search parameters - address and API key
parameters = {"address": "Venice Blvd. and Moore st, Los Angeles",
              "key": AUTH_KEY}
```
```python
import folium
from folium.plugins import MarkerCluster

m = folium.Map(location=[34.0453119,-118.3083065], zoom_start=12)
marker_cluster = MarkerCluster().add_to(m)
```

## Roadmap

See the [open issues](https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper/issues) for a list of proposed features (and known issues).

- [Top Feature Requests](https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper/issues?q=label%3Aenhancement+is%3Aopen+sort%3Areactions-%2B1-desc) (Add your votes using the 👍 reaction)
- [Top Bugs](https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper/issues?q=is%3Aissue+is%3Aopen+label%3Abug+sort%3Areactions-%2B1-desc) (Add your votes using the 👍 reaction)
- [Newest Bugs](https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper/issues?q=is%3Aopen+is%3Aissue+label%3Abug)

## Support

ykimdeveloper - message me for any questions

Reach out to the maintainer at one of the following places:

- [GitHub issues](https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper/issues/new?assignees=&labels=question&template=04_SUPPORT_QUESTION.md&title=support%3A+)
- Contact options listed on [this GitHub profile](https://github.com/ykimdeveloper)

## Project assistance

If you want to say **thank you** or/and support active development of MAPS-Great-Streets-Survey-ykimdeveloper:

- Add a [GitHub Star](https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper) to the project.
- Tweet about the MAPS-Great-Streets-Survey-ykimdeveloper.
- Write interesting articles about the project on [Dev.to](https://dev.to/), [Medium](https://medium.com/) or your personal blog.

Together, we can make MAPS-Great-Streets-Survey-ykimdeveloper **better**!

## Contributing

First off, thanks for taking the time to contribute! Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make will benefit everybody else and are **greatly appreciated**.


Please read [our contribution guidelines](docs/CONTRIBUTING.md), and thank you for being involved!

## Authors & contributors

The original setup of this repository is by [yosep kim](https://github.com/ykimdeveloper).

For a full list of all authors and contributors, see [the contributors page](https://github.com/ykimdeveloper/maps-great-streets-survey-ykimdeveloper/contributors).

## Security

MAPS-Great-Streets-Survey-ykimdeveloper follows good practices of security, but 100% security cannot be assured.
MAPS-Great-Streets-Survey-ykimdeveloper is provided **"as is"** without any **warranty**. Use at your own risk.

_For more information and to report security issues, please refer to our [security documentation](docs/SECURITY.md)._

## License

This project is licensed under the **MIT license**.

See [LICENSE](LICENSE) for more information.
