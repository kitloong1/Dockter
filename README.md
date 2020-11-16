<p align="center">
  <img width="256" height="256" src="resources/icons/256x256.png">
</p>

<p align="center">
  <img alt="GitHub" src="https://img.shields.io/github/license/oslabs-beta/Dockter?color=blue">
  <img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/oslabs-beta/Dockter?color=pink">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/oslabs-beta/Dockter?color=green">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/oslabs-beta/Dockter?style=social">  
</p>
<br/>
<p align="center">
  <a href="https://www.producthunt.com/posts/dockter?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-dockter" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=274669&theme=dark" alt="Dockter - A low-overhead, open-source Docker log management tool | Product Hunt" style="width: 250px; height: 54px;" width="200" height="54" /></a>
</p>

# Appendix
<!-- [_Companion Website_](#companion-website)   -->
[_What is Dockter_](#overview)  
[_Prerequisites_](#prerequisites)  
[_Quick Start_](#quick-start)  
[_Built With_](#built-with)  
[_Contributions_](#contributions)  
[_Testing_](#testing)  
[_Authors_](#authors)  
[_Beta_](#beta)

# What is Dockter?

> Dockter v0.1.0 is a low-overhead , open source Docker log management tool built for:
>
> - **Real-time Log Collection** - communicating with the Docker Engine API to access container streams and collect live logs
> 
> <br/>
> <p align="center">
>   <img width="700" src="https://media.giphy.com/media/tCRgZysaNlDViounfv/giphy.gif">
> </p>
> <br/>
> 
> - **Log Aggregation** - Storing container logs into a centralized database
>
> <br/>
> <p align="center">
>   <img width="700" src="https://media.giphy.com/media/BxN3pd5okEMaG6auPw/giphy.gif">
> </p>
> <br />
> 
> - **Filter & Search Capability** - Analyze and extract meaningful data through filter and search 
>
> <br/>
> <p align="center">
>   <img width="700" src="https://media.giphy.com/media/ueqUbnusHfOAVJdOXu/giphy.gif">
> </p>
> <br />

<!-- # Companion Website

> - [Dockter.io](https://www.dockter.io/)
> - [Give us some claps on medium!](https://kylewhang.medium.com/a-remedy-for-containerized-illness-f9d0c5e49f6) -->

# Prerequisites

> Ensure that you have the following installed and running on your machine:
>
> - [Docker Client](https://www.docker.com/get-started)
> - [Running Docker Container(s)](https://docs.docker.com/get-started/)
> - [MongoDB](https://docs.mongodb.com/manual/administration/install-community/)
> - [Yarn Package Manager](https://classic.yarnpkg.com/en/docs/getting-started)

# Quick Start

> First, clone our repo by running either:
>
> ```
> git clone git@github.com:oslabs-beta/Dockter.git
> ```
>
> _or_
>
> ```
> gh repo clone oslabs-beta/Dockter
> ```
>
> (_if you have the [Github CLI](https://cli.github.com/) installed_)
> in your terminal.
> Next, `cd` into your cloned Docktor repository and run the following command to install all necessary dependencies
>
> ```
> yarn
> ```
>
> Last, run this command to start Dockter on your machine. It's as easy as that!
>
> ```
> yarn start
> ```

# Built With

> - Docker - Platform as a Service
> - React (Hooks) - Front-end Library
> - Electron - Desktop Application Framework
> - Tailwind CSS
> - MongoDB - noSQL Document Oriented database
> - Mongoose - Object Data Modeling Library
> - Jest - Testing Framework
> - Enzyme - React Testing Utility
> - ESlint - Javascript Linting Tool
> - Yarn - Package Manager

# Contributions

> Dockter welcomes any ideas and/or contributions to its codebase. Please click the button below to reach out to us at with any questions or even if you'd just like to talk shop. We'd love to hear from you!  
>  <br> > _To run the application in development mode, please clone the Docktor repository to your local machine and run the following commands in your terminal:_
>
> ```
> yarn
> ```
>
> ```
> yarn dev
> ```
>
>    <br>
> <p align="center">
> <a href="mailto:dockter.contributions@gmail.com?subject=Contribution Requests or Question"><img src="https://img.shields.io/badge/Contribute%20Now!-%23DD0031.svg?&style=for-the-badge&logoColor=white"/></a>
> </p>

# Testing

_To perform tests on the Dockter codebase, please clone the repository to your local machine and run the following commands in your terminal:_

> ```
> yarn
> ```
>
> ```
> yarn build
> ```
>
> ```
> yarn test
> ```

# Authors

Benjamin Brower [@github](https://github.com/bbrower21) [@linkedIn](https://www.linkedin.com/in/ben-brower-80660073/)  
Anup Ramdass [@github](https://github.com/anrax) [@linkedIn](https://www.linkedin.com/in/anupramdass/)  
Nancy Koushoult [@github](https://github.com/noodlemonkey) [@linkedIn](https://www.linkedin.com/in/nancy-kousholt-a6a2071b9/)  
Kyle Whang [@github](https://github.com/shaisle) [@linkedIn](https://www.linkedin.com/in/kylewhang/)  
Samuel Kim [@github](https://github.com/samuy) [@linkedIn](https://www.linkedin.com/in/whalewhalewhale/)

# Features In Beta

_The Dockter team is dedicated to working around the clock to ensure proper maintainence and the addition of even more robust features. The following are coming soon:_

> - Analysis of Log Metrics - real-time log statistics will be available to the user on the Dockter dashboard in a visualized format with the capability to dynamically focus on logs that may require higher levels of oversight
> - Container management - users will be able to remove, stop, and start containers from within the Dockter dashboard
