<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GNU Affero General Public License v3.0 License][license-shield]][license-url]

<div align="center">
  <h3 align="center">Talium</h3>
  <p align="center">
    Talium document vault
    <br />
    <a href="https://github.com/JelleBuning/talium/issues">Report Bug</a>
    ·
    <a href="https://github.com/JelleBuning/talium/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



## About The Project
Talium is a self-hosted, secure document vault designed to help individuals and teams organize, store, and protect sensitive digital assets. Built with a focus on absolute privacy and high performance, Talium acts as a centralized repository for your critical files, contracts, financial records, and personal data. 

By eliminating reliance on third-party cloud providers, Talium gives you complete ownership of your data, wrapped in an intuitive interface that makes document retrieval and management effortless.

### Features
* **Secure Storage & Encryption:** Protects your documents at rest and in transit, ensuring that sensitive data remains accessible only to authorized users.
* **Intelligent Tagging & Metadata:** Organize your files your way. Filter, search, and categorize documents using custom tags and metadata for instant retrieval.
* **Modern Architecture:** Built adhering strictly to SOLID principles and clean architecture design patterns, ensuring the codebase is highly maintainable, scalable, and easy to extend.

### Built With

* [Framework/Language Name](https://example.com)
* [Library Name](https://example.com)

## Getting Started
Setting up this solution on your local machine is straightforward and will enable you to fully utilize its capabilities. This guide will walk you through the necessary steps to get everything running smoothly.

Before beginning, ensure that your development environment is properly configured. Having the required software and dependencies installed will prevent common issues and streamline the process.

### Installation
This installation method utilizes Docker Compose for a streamlined setup. Ensure you have Docker and Docker Compose installed on your system.

1.  **Create a `docker-compose.yml` file:**

    Create a new file named `docker-compose.yml` in a directory of your choice. Copy and paste the following content into it:

    ```yaml
    version: '3.4'
    name: talium
    services:
      talium:
        container_name: "talium"
        image: ghcr.io/JelleBuning/talium
    ```

2.  **Run Docker Compose:**

    In the same directory as your `docker-compose.yml` file, execute the following command:

    ```bash
    docker-compose up -d
    ```

    This command will download the necessary images, create the containers, and start them in detached mode.

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/feature-title`)
3. Commit your Changes (`git commit -m 'Added feature'`)
4. Push to the Branch (`git push origin feature/feature-title`)
5. Open a Pull Request


<!-- LICENSE -->
## License
Distributed under the GNU Affero General Public License v3.0 License. See `LICENSE` for more information.


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/JelleBuning/talium.svg?style=for-the-badge
[contributors-url]: https://github.com/JelleBuning/talium/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/JelleBuning/talium.svg?style=for-the-badge
[forks-url]: https://github.com/JelleBuning/talium/network/members
[stars-shield]: https://img.shields.io/github/stars/JelleBuning/talium.svg?style=for-the-badge
[stars-url]: https://github.com/JelleBuning/talium/stargazers
[issues-shield]: https://img.shields.io/github/issues/JelleBuning/talium.svg?style=for-the-badge
[issues-url]: https://github.com/JelleBuning/talium/issues
[license-shield]: https://img.shields.io/github/license/JelleBuning/talium.svg?style=for-the-badge
[license-url]: https://github.com/JelleBuning/talium/blob/master/LICENSE
