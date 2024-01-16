<br/>
<p align="center">
  <a href="https://github.com/jalexmatey/ubuntu-home-server-infra">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">ubuntu-home-server-infra</h3>

  <p align="center">
    An ansible repo for my home servers running Ubuntu.
    <br/>
    <br/>
    <a href="https://github.com/jalexmatey/ubuntu-home-server-infra"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/jalexmatey/ubuntu-home-server-infra">View Demo</a>
    .
    <a href="https://github.com/jalexmatey/ubuntu-home-server-infra/issues">Report Bug</a>
    .
    <a href="https://github.com/jalexmatey/ubuntu-home-server-infra/issues">Request Feature</a>
  </p>
</p>

![Stargazers](https://img.shields.io/github/stars/jalexmatey/ubuntu-home-server-infra?style=social) ![Issues](https://img.shields.io/github/issues/jalexmatey/ubuntu-home-server-infra) ![License](https://img.shields.io/github/license/jalexmatey/ubuntu-home-server-infra) 

## Table Of Contents

- [Table Of Contents](#table-of-contents)
- [About The Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Updating the servers](#updating-the-servers)
  - [Deploying the docker containers to a server](#deploying-the-docker-containers-to-a-server)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
  - [Creating A Pull Request](#creating-a-pull-request)
- [License](#license)
- [Authors](#authors)
- [Acknowledgements](#acknowledgements)

## About The Project

![Screen Shot](images/screenshot.png)

A centralised place for my home servers running Ubuntu's IaC to live.

Why setup an Ubuntu server with IaC?:
* To quickly and safely get a new Ubuntu server device exactly how I want it set up, with minimal clicking of the mouse.
* I don't need to remember every thing I have done.
* It's fun!

## Built With

* [Ansible](https://www.ansible.com/)

## Getting Started


### Prerequisites

You will need a SSH key on the target server setting up, you can use `ssh-copy-id` to do this. More info can be found [here](https://www.ssh.com/academy/ssh/copy-id).


### Installation

1. Clone or download this repository to your local drive.
2. Copy `./example.inventory.yml` to `./inventory.yml` and edit.
3. Run `ansible-galaxy install --role-file requirements.yml`.

## Usage

### Updating the servers

1. Run `ansible-playbook ./update.yml`.

### Deploying the docker containers to a server

1. Run `ansible-playbook ./docker-containers.yml --ask-become-pass`.

## Roadmap

See the [open issues](https://github.com/jalexmatey/ubuntu-home-server-infra/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/jalexmatey/ubuntu-home-server-infra/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/jalexmatey/ubuntu-home-server-infra/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/jalexmatey/ubuntu-home-server-infra/blob/main/LICENSE.md) for more information.

## Authors

* **Jack Alexander** - *DevOps Engineer* - [Jack Alexander](https://github.com/jalexmatey) - *Everything*

## Acknowledgements

* [ShaanCoding](https://github.com/ShaanCoding/)
* [Othneil Drew](https://github.com/othneildrew/Best-README-Template)
* [ImgShields](https://shields.io/)
