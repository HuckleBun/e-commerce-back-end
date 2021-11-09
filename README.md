
![Repo Size][repo-size]
![Language][GitHub-language]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
![MIT License][license-shield]

<br />
<p align="center">
<h1 align="center" id="e-commerce">E-Commerce 🗃</h1>

<p align="center">
As a manager at an internet retail company, I want a back end for my e-commerce website that<br /> uses the latest technologies, so my company can compete with other e-commerce companies.
<br />
<a href="#description"><strong>Explore the docs »</strong></a>
<br />
<br />
<a href="https://drive.google.com/file/d/1w7MUwn_04KkbVfFoPnK2XDOgXQhl0H1q/view?usp=sharing">View Demo</a>
.
<a href="https://github.com/Derimarg/e-commerce/issues">Report Bug</a>
·
<a href="https://github.com/Derimarg/e-commerce/issues">Request Feature</a>
</p>
</p>
<br />
<br />

<details open="open">
<summary>Table of Contents</summary>
<ul>
<li><a href="#description">Description</a></li>
<li><a href="#technologies">Technologies</a></li>
<li><a href="#how-to-download">Download</a></li>
<li><a href="#installation">Installation</a></li>
<li><a href="#prerequisites">Prerequisites</a></li>
<li><a href="#usage">Usage</a></li>
<li><a href="#roadmap">Roadmap</a></li>
<li><a href="#contributing">Contributing</a></li>

<li><a href="#questions">Questions</a></li>
<li><a href="#license">License</a></li>
</ul>
</details>

---
  
## Description
  
GIVEN a functional `Express.js API`
- Adding to the `database a name, MySQL username, and MySQL password` to an environment variable file, will be able a connect to database using Sequelize.
- Entering schema and seed commands, a development database is created and is seeded with test data.
- Entering the command to invoke the application, server will be started and the Sequelize models are synced to the MySQL database.
- Opening the `API GET routes in Insomnia Core` for categories, products, or tags, the data for each of these routes is displayed in a formatted JSON.
- Testing `API POST, PUT, and DELETE routes in Insomnia Core`, successfully will be able to create, update, and delete data in my database.

### Example:

  Design of database schema as shown in the following image:
<br />
<br />
<p><h3>- Database Connection and Seeds</h3><br /><img src="./assets/images/sql.gif" alt="Database connection" width="auto" height="auto"></p>
<br />
<br />
<p><h3>- Product Routes</h3><br /><img src="./assets/images/products.gif" alt="Product routes" width="auto" height="auto"></p>
<br />
<br />
<p><h3>- Category Routes</h3><br /><img src="./assets/images/categories.gif" alt="Category routes" width="auto" height="auto"></p>
<br />
<br />
<p><h3>- Tag Routes</h3><br /><img src="./assets/images/tags.gif" alt="Tag routes" width="auto" height="auto"></p>
<br />
<br />

## Technologies

- <p><a href="https://nodejs.org/">Node.js</a></p>
- <p><a href="https://dev.mysql.com">MySQL</a></p>
- <p><a href="https://www.npmjs.com/">NPM</a></p>
- <p><a href="https://www.npmjs.com/package/mysql2">NPM Node MySQL 2</a></p>
- <p><a href="https://www.npmjs.com/package/sequelize">NPM Sequelize</a></p>
- <p><a href="https://www.npmjs.com/package/dotenv">NPM Dotenv</a></p>

[Back To Top](#e-commerce)

---

## How to Download

- Simply copy the **SSH** to the terminal or Download the **ZIP File**:

## Installation

- Use the follow command at your terminal, **git clone** (Create a working copy at your local repository):

  ```
  git clone git@github.com:Derimarg/e-commerce.git
  ```

- After cloned the repository, create your own repository, copy the files to your repository and type in your terminal the follow commands. 

  ```
  git status

  git add -A

  git commit -m "Message to commit."

  git push or git push origin main
  ```

## Prerequisites

1.- Before of using this application, is require to install dependencies, run the following command in your terminal:

  ```
  npm i
  ```

2.- At the root of the project, create a file `.env`, and insert your MySQL info:

```
DB_NAME='ecommerce_db''
DB_USER='your_MySQL_username'
DB_PW='your_MySQL_password'
```

3.- At the root of your project, open your terminal and run the following commands:

    1.- mysql -u root -p

    2.- Enter your MySQL password

    3.- source db/schema.sql

    4.- quit

    5.- npm run seed
    
    6.- npm start

[Back To Demo](#example)

---

## Usage

This is a open source program, feel free to use it, contact me to request features.    

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/Derimarg/e-commerce/issues) for a list of proposed features (and known issues).

[Back To Top](#e-commerce)

---

<!-- CONTRIBUTORS -->
## Contributing

Contributions are part of this open source project. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/name-of-feature`)
3. Commit your Changes (`git commit -m "Add some feature"`)
4. Push to the Branch (`git push origin feature/name-of-feature`)
5. Open a Pull Request



## Questions

For additional help or questions about collaboration, contact me at: derimargray@gmail.com

- GitHub - [Derimarg](https://github.com/Derimarg/)
- Linkedin - [Derimar Gray](https://www.linkedin.com/in/derimar-gray-676275132/)
- Project Repository Link: https://github.com/Derimarg/e-commerce
- walkthrough video: https://drive.google.com/file/d/1w7MUwn_04KkbVfFoPnK2XDOgXQhl0H1q/view?usp=sharing

[Back To Top](#e-commerce)

---


## License

MIT License

Copyright (c) 2021 Derimar Gray

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
  

[repo-size]: https://img.shields.io/github/repo-size/Derimarg/e-commerce?style=for-the-badge
[GitHub-language]: https://img.shields.io/github/languages/top/Derimarg/e-commerce?color=yellow&style=for-the-badge
[contributors-shield]: https://img.shields.io/github/contributors/Derimarg/e-commerce.svg?style=for-the-badge
[contributors-url]: https://github.com/Derimarg/e-commerce/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Derimarg/e-commerce.svg?color=9cf&style=for-the-badge
[forks-url]: https://github.com/Derimarg/e-commerce/network/members
[stars-shield]: https://img.shields.io/github/stars/Derimarg/e-commerce.svg?color=blueviolet&style=for-the-badge
[stars-url]: https://github.com/Derimarg/e-commerce/stargazers
[issues-shield]: https://img.shields.io/github/issues/Derimarg/e-commerce.svg?style=for-the-badge
[issues-url]: https://github.com/Derimarg/e-commerce/issues
[license-shield]: https://img.shields.io/static/v1?label=license&message=MIT&color=yellowgreen.svg&style=for-the-badge
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/derimar-gray-676275132/
  
