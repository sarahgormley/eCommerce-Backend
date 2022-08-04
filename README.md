# eCommerce Backend

![GitHub](https://img.shields.io/badge/license-Apache-yellow.svg)


## Table Of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)
* [Contributions](#contributions)
* [Questions](#questionscontact)
* [Walkthrough](#walkthrough)


## Description

Internet retail, also known as e-commerce, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

The purpose of this eCommerce app was to create the backend for an ecommerce site, using Express.js & MySQL. This app uses API routes to quickly access the information on products, categories, and tags. These can all be easily created, read, updated, and deleted. 


## Installation
To install the dependencies required for this repository, please run the following command:

```
npm install 
```


## Usage
Make sure you download all the required packages (Inquirer, Sequelize, MySQL, DotEnv).
Open the file in VS code and open the terminal from the 'db' folder. 
From there, run the command 
```
mysql -u root -p
```
And log into MySQL. Next, run the command
```
source schema.sql
```
Whilst keeping this window open, open the terminal again, this time from the application folder, and run the following commands:
```
npm run seed

node server.js
```
Once this has successfully run, a notification will appear in the terminal stating 
```
App listening on port ${PORT}!
```
With your chosen localhost port specified. 

After this, navigate to Insomnia to using the app. 


## Credits
Sarah Gormley


## License
This repository is licenced under Apache.

## Contributions
To contribute to this project, please Email me :) See below.

## Questions/Contact
For questions and comments related to this repository, please email me at: sarah.gormley39@gmail.com. Alternatively, view my other projects at [sarahgormley](https://github.com/sarahgormley).

## Walkthrough
[Click here to watch a video demonstration of the eCommerce Backend in action](https://drive.google.com/file/d/1pIDg1nMMKzsz4F19acsc7p7ntPEZmkH3/view?usp=sharing)
