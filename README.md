# text-editor
<h1 align="center"> PWA - TEXT EDITOR 🚩</h1>
<br>
<p align="center">
  <a href="#">
  <img alt="nodejs" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" target="_blank" />
  <a href="#">
  <img alt="expressjs" src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" target="_blank" />
  <a href="#">
  <img alt="javascript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascriptlogoColor=black" target="_blank" />
  <a href="#">
  <img alt="npm" src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" target="_blank" />
  <a href="#">
  <img alt="css3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" target="_blank" />
  <a href="#">
  <img alt="html5" src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white" />
  <a href="#">
  <img alt="heroku" src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white" target="_blank" />
  <br>
  <a href="#">
  <img alt="watchers" src="https://img.shields.io/github/watchers/ThiHoangPham/text-editor?color=%2346b946&style=flat-square" target="_blank" />
  <a href="#">
  <img alt="rep size" src="https://img.shields.io/github/repo-size/ThiHoangPham/text-editor?style=flat-square" target="_blank" />
  <a href="https://github.com/ThiHoangPham/text-editor/blob/main/LICENSE">
  <img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-yellow.svg?style=flat-square" target="_blank" />
  </a>
  <a href="#">
  <img alt="fork" src="https://img.shields.io/github/forks/ThiHoangPham/text-editor.svg?style=flat-square" target="_blank" />
  <a href="#">
  <img alt="repo star" src="https://img.shields.io/github/stars/ThiHoangPham/text-editor?color=%23ff00bf&style=flat-square" target="_blank" />
  </a>
  <a href="#">
  <img alt="contributors" src="https://img.shields.io/github/contributors/ThiHoangPham/text-editor?style=flat-square" target="_blank" />
  </a>
  <a href="#">
  <img alt="top language" src="https://img.shields.io/github/languages/top/ThiHoangPham/text-editor?color=%23ff4000&style=flat-square" target="_blank" />
  </a>
  <a href="#">
  <img alt="issue open" src="https://img.shields.io/github/issues-raw/ThiHoangPham/text-editor?style=flat-square" target="_blank" />
  </a>
</p>
<hr>

  <h3 align="center">
    <p align="center">
      <a href="https://github.com/ThiHoangPham/text-editor"><strong>Explore the docs »</strong></a>
      <br />
      <br />
      <a href="#live-demo-heroku">Demo</a>
      ·
      <a href="https://github.com/ThiHoangPham/text-editor/issues">Report Bug</a>
      ·
      <a href="https://github.com/ThiHoangPham/text-editor/issues">Request Feature</a>
    </p>
  </table>

  <details>
    <summary>Table of Contents</summary>
    <ul>
      <li><a href="#about-the-project">About The Project</a>
      <li><a href="#user-story">User Story</a></li>
      <li><a href="#acceptance-criteria">Acceptance Criteria</a></li>
      <li><a href="#live-demo-heroku">Live Demo Heroku</a></li>
      <li><a href="#installation">Installation</a></li>
      <li><a href="#usage">Usage</a></li>
      <li><a href="#contributor">Contributor</a></li>
      <li><a href="#contribution">Contribution</a></li>
      <li><a href="#license">License</a></li>
      <li><a href="#more-about-me">Questions & Contact</a></li>
    </ul>
  </details>

  <br />

# About The Project
  Build a Text Editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

  ![text-editor-demo-gif](./client/src/images/Text-Editor.gif)

# User Story
```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```
# Acceptance Criteria
```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

# Live Demo Heroku: 
<a href="https://just-another-text-editor.herokuapp.com/">
  <img alt="live demo heroku" src="https://img.shields.io/badge/Demo-Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white" target="_blank" />
  </a>

# Installation
```
Clone/Fork the Repo to your Local, and run command:

`npm install`
```
# Usage
```
Run the following command at the root of your project:

`npm start`
```
# Contributor
<a href="https://github.com/ThiHoangPham/text-editor">
  <img alt="contributor" src="https://contrib.rocks/image?repo=ThiHoangPham/text-editor" target="_blank" />
  </a>

# Contribution
This how you can contribute to this project:
```
> Clone the project to your local 
> Create your own branch
> Add contribution codes/commit/push to remote repo
> Create a pull request
```
# License
  Distributed under the [MIT](https://github.com/ThiHoangPham/text-editor/blob/main/LICENSE).

# More About Me
  <a href="https://github.com/ThiHoangPham">
  <img alt="profile-github" src="https://img.shields.io/badge/Profile-GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank" />
  <a href="https://thihoangpham.github.io/updated-professional-materials/">
  <img alt="portfolio-page" src="https://img.shields.io/badge/Portfolio-Page-FEAA2D?style=for-the-badge&logo=deezer&logoColor=white" target="_blank" />
  <a href="mailto:thaihoangpham2008@gmail.com">
  <img alt="email-adam" src="https://img.shields.io/badge/Email to me-Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank" />
  </br>
  <p align ="right"><a href="#">↥ back to top</a></p>

- - -

© 2021 Thai Hoang Pham (Adam): PWA - Text Editor
