<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project

Simple filebeat ansible role that deploys custom filebeat configuration on both Redhat and Debian systems.

### Built With

* [Ansible](https://ansible.com)
* [Yaml](https://yaml.com)

## Getting Started

ansible-playbook -i {{ your_inventory_file }} filebeat.yml tags=debian,config


### Prerequisites

Ansible version 2.9.0 +

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/m-stojanovic/filebeat-ansible-role/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

Milos Stojanovic - [@linkedin](https://www.linkedin.com/in/infomilosstojanovic/)

Project Link: [https://github.com/m-stojanovic/filebeat-ansible-role](https://github.com/m-stojanovic/filebeat-ansible-role)
