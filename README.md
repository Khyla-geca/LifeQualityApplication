

<details open="open">
  <summary><h2 style="display: inline-block">Table of Content</h2></summary>
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
    <li><a href="#links">Links</a></li>
  </ol>


## About The Project

![Product Name Screen Shot](src/img/screenshot.jpeg)

This is a Javascript web app that fetches cities life quality data from the [Teleport](https://developers.teleport.org/api/getting_started/) free API, and displays them.

The user can discover info about its preferred city via search input.

Statistics include the total score of the city, a brief description and the partial scores of various indicators such as: housing, cost of living, startups, venture capital, travel connectivity, commute, business freedom, safety, healthcare, education, environmental quality, economy, taxation, internet access, leisure & culture, tolerance and outdoors. 

### Built With

* [HTML 5](https://developer.mozilla.org/en-US/docs/Glossary/HTML)
* [CSS 3](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript?retiredLocale=it)
* [Webpack 5](https://webpack.js.org/blog/2020-10-10-webpack-5-release/)
* [Lodash](https://lodash.com/)
* [Axios](https://github.com/axios/axios)

## Getting Started

### Prerequisites

Running the application requires [Node](https://nodejs.org/en/) to be installed on your operating system.

You can then install the latest version of npm from your terminal with the command:

  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repository locally with the git command:

   ```sh
   git clone https://github.com/Khyla-geca/LifeQualityApplication
   ```

2. Install NPM packages:

   ```sh
   npm install
   ```
  
3. Build from source:

   ```sh
   npm run build
   ```
4. Open build/index.html

## Usage

The user can type a city on the search input. City name must be typed in English. When the form is submitted, a 'get' axios request to the Teleport API fetches the data 
of the city. These life quality data are then displayed on the interface.

## Links 

Project Repository:  [Home Sweet Home](https://github.com/Khyla-geca/LifeQualityApplication)

Project Website:  [Home Sweet Home - Netlify](https://lifequalityapplication.netlify.app/)






