<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/MarkVI2/OhmWay">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">⚡ OhmWay</h3>
<h4 align="center"><em>Previously known as MazeSolver-418-24</em></h4>

  <p align="center">
    Find the path of least resistance through any maze using the power of electrical circuits
    <br />
    <a href="https://github.com/MarkVI2/OhmWay"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/MarkVI2/OhmWay">View Demo</a>
    ·
    <a href="https://github.com/MarkVI2/OhmWay/issues">Report Bug</a>
    ·
    <a href="https://github.com/MarkVI2/OhmWay/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
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
    <li><a href="#features">Features</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![OhmWay Screen Shot][product-screenshot]](https://example.com)

OhmWay is an innovative maze-solving application that transforms maze-solving into an electrical circuit problem. By representing maze paths as resistors and applying voltage, we find the optimal path through electrical current flow - proving that sometimes the most elegant solutions come from unexpected places.

The project was inspired by AlphaPhoenix's fascinating demonstration of solving mazes using real electrical circuits. We took that concept and brought it into the digital realm.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* ![Python](https://img.shields.io/badge/python-3.8+-yellow?style=for-the-badge&logo=python&logoColor=white)
* ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
* ![PySpice](https://img.shields.io/badge/PySpice-blue?style=for-the-badge)
* ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get OhmWay running locally, follow these steps:

### Prerequisites

* Python 3.8+
* ngspice
* PySpice
  ```sh
  pip install PySpice
  ```

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/MarkVI2/OhmWay.git
   ```
2. Install Python packages
   ```sh
   pip install -r requirements.txt
   ```
3. Install ngspice (System dependent)
   ```sh
   # Ubuntu/Debian
   sudo apt-get install ngspice
   # macOS
   brew install ngspice
   ```
4. Run the application
   ```sh
   python app.py
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE -->
## Usage

OhmWay converts maze images into electrical circuits using PySpice and ngspice. Each open path in the maze becomes a resistor, and by analyzing voltage drops across the network, we determine the optimal path from start to finish.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FEATURES -->
## Features

* Real-time maze to circuit conversion
* Interactive web interface
* Path visualization with voltage mapping
* Support for various maze formats
* Optimal pathfinding using electrical principles

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Initial maze to circuit conversion
- [x] Basic web interface
- [ ] Performance optimization for larger mazes
- [ ] Enhanced visualization of current flow
- [ ] Support for multiple path finding criteria
    - [ ] Shortest path
    - [ ] Alternative paths
- [ ] Pipeline optimization
- [ ] API development

See the [open issues](https://github.com/MarkVI2/OhmWay/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Key Areas for Contribution
* Algorithm optimization
* UI/UX improvements
* Documentation
* Circuit simulation enhancements
* Testing and validation

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Atharv Ashish Garg - [@aviator_gator](https://x.com/aviatorGator141) - mark.atharv@gmail.com
Swastick Paliwal - 

Project Link: [https://github.com/MarkVI2/OhmWay](https://github.com/MarkVI2/OhmWay)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [AlphaPhoenix](https://youtube.com/@AlphaPhoenixChannel) for the original inspiration
* The PySpice community for their excellent circuit simulation tools
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template) for the README template

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/MarkVI2/OhmWay.svg?style=for-the-badge
[contributors-url]: https://github.com/MarkVI2/OhmWay/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/MarkVI2/OhmWay.svg?style=for-the-badge
[forks-url]: https://github.com/MarkVI2/OhmWay/network/members
[stars-shield]: https://img.shields.io/github/stars/MarkVI2/OhmWay.svg?style=for-the-badge
[stars-url]: https://github.com/MarkVI2/OhmWay/stargazers
[issues-shield]: https://img.shields.io/github/issues/MarkVI2/OhmWay.svg?style=for-the-badge
[issues-url]: https://github.com/MarkVI2/OhmWay/issues
[license-shield]: https://img.shields.io/github/license/MarkVI2/OhmWay.svg?style=for-the-badge
[license-url]: https://github.com/MarkVI2/OhmWay/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
