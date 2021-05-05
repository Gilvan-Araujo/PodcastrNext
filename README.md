<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the podcastrnext and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** gilvan-araujo, podcastrnext,mail, Podcastr, Application developed for the fifth edition of the Next Level Week by Rocketseat.
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/gilvan-araujo/podcastrnext">
    <img src="public/logo.svg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Podcastr</h3>

  <p align="center">
    Application developed for the fifth edition of the Next Level Week by Rocketseat.
    <br />
    <a href="https://github.com/gilvan-araujo/podcastrnext">View Demo</a>
    ·
    <a href="https://github.com/gilvan-araujo/podcastrnext/issues">Report Bug</a>
    ·
    <a href="https://github.com/gilvan-araujo/podcastrnext/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Podcastr Screenshot](https://user-images.githubusercontent.com/45008443/117197883-b9f27c00-adbe-11eb-910a-60bdcd829d53.png)](https://podcastr-next-chi.vercel.app/)

### Built With

* [React JS](https://reactjs.org/)
* [Next.JS](https://nextjs.org/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* yarn

  ```sh
  curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
  echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
  sudo apt update && sudo apt install --no-install-recommends yarn
  export PATH="$PATH:`yarn global bin`"
  ```

  See if it's installed with

  ```sh
  yarn --version
  ```

* npm and node.js

  ```sh
  sudo apt install npm nodejs
  ```

### Installation

1. Clone the podcastrnext

   ```sh
   git clone https://github.com/gilvan-araujo/podcastrnext.git
   ```

2. Install yarn packages

   ```sh
   yarn add
   ```

<!-- USAGE EXAMPLES -->
## Usage

This project was designed as a listening hub for the Faladev podcast made by Rocketseat. It also has pages for every individual podcast, featuring a description and everyone that participated in that episode.

![playing-screen](https://user-images.githubusercontent.com/45008443/117198997-10ac8580-adc0-11eb-939d-85dc5a606b60.png)
*Screen when a podcast is being played* &nbsp;

![description-screen](https://user-images.githubusercontent.com/45008443/117199002-11451c00-adc0-11eb-9f83-92f058f139fa.png)
*Screen containing the description of a podcast* &nbsp;

<!-- ROADMAP -->
## Roadmap

### Personal Features

* [ ] Improve responsivity
  * [ ] Media queries for mobile
  * [ ] Implement Next PWA
* [ ] Different color schemes
  * [ ] Dark theme
  * [ ] Light theme and toggle
* [ ] New functionalities
  * [ ] Add and remove podcasts

### Issues

See the [open issues](https://github.com/gilvan-araujo/podcastrnext/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

Gilvan Araújo - gilvanjunior@protonmail.com

Project Link: [https://github.com/gilvan-araujo/podcastrnext](https://github.com/gilvan-araujo/podcastrnext)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/gilvan-araujo/podcastrnext.svg?style=for-the-badge
[contributors-url]: https://github.com/gilvan-araujo/podcastrnext/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/gilvan-araujo/podcastrnext.svg?style=for-the-badge
[forks-url]: https://github.com/gilvan-araujo/podcastrnext/network/members
[stars-shield]: https://img.shields.io/github/stars/gilvan-araujo/podcastrnext.svg?style=for-the-badge
[stars-url]: https://github.com/gilvan-araujo/podcastrnext/stargazers
[issues-shield]: https://img.shields.io/github/issues/gilvan-araujo/podcastrnext.svg?style=for-the-badge
[issues-url]: https://github.com/gilvan-araujo/podcastrnext/issues
[license-shield]: https://img.shields.io/github/license/gilvan-araujo/podcastrnext.svg?style=for-the-badge
[license-url]: https://github.com/gilvan-araujo/podcastrnext/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/gilvan-araujo
