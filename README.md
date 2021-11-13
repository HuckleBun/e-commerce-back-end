# Employee Tracker

## License
This application is under the cover of the MIT license.
![badge](https://img.shields.io/badge/license-MIT-brightgreen)

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Demo](#demo)
- [Usage](#usage)
- [Contribution](#contribution)
- [Connect](#connect)

## Description
This is a back-end application that allows you to test GET, POST, PUT, and DELETE routes to add, remove, or modify Products, and Categories and Tags or said products. You can test is by using programs such as [**Insomnia**](https://insomnia.rest/)

## Installation

- Use the follow command at your terminal, **git clone** (Create a working copy at your local repository):

```
git clone git@github.com:hucklebun/employee-tracker.git
```

Once cloned, move into the directory of this project inside the terminal, then enter into your terminal:

```
npm i
```

You will want to make sure you have mysql properly installed onto your machine. If installed, enter the following into your terminal:

```
mysql -u root -p
```

You will then be prompted for your mysql password. Once you are logged into mysql inside the terminal, enter the following commands:

```
source db/schema.sql;
```
```
npm run seed
```

Once everything runs with no errors, you can quit out of mysql by entering **quit**.

Once you have properly installed NPM and ran all the sql commands within the mysql terminal, enter this into your terminal:

```
npm start
```

This will run the program and you are all good to go!

## Demo
https://user-images.githubusercontent.com/62036600/141602377-9feebff7-c5c5-46f3-8999-a19aeb48436b.mp4

## Usage
GET, POST, PUT, and DELETE routes to edit back-end database

## Contribution
Micah Duehring (hucklebun)

## Have questions? Connect with me.
GitHub: [hucklebun](https://github.com/hucklebun/)
</br>
Email: micah@theduehrings.com
