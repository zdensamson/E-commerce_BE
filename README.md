# E-commerce Back End

## Description 

For this project I was provided with seed data and basic scaffolding of a potential e-commerce back end. 
My contribution to this code base was working with the Sequelize ORM to build out the **Moldels**, **Associations**, & API **Routes** -- in order for a future state front end to be able to make calls to an express server, and recieve JSON data from respective routes.


A video example can be found here: [Walkthrough](https://drive.google.com/file/d/1bzSdQbp-f__sS0FsukDaDoQhKxE69XiM/view)


## Installation
To install dependencies, run the following command:
```
npm install
```
As this application requires the MySQL2 package for usage on a local machine-- any user must also provide their own username & password credentials to the **.env** file in this repository. 

## Utilized technologies 

This application was built using __JavaScript__.

In order to bring additional functionality to the project the following packages/technologies were implemented:
* Node.js
* MySQL2
* Express.js
* Sequelize

All local data persistance was handled by **MySQL2**. I used **Sequelize** to create the table schema (models) and respective model methods to query the local database. **Express.js** was used to instantiate a server and set up routes to perform CRUD operations on the local database. 

## Challenges

While I understood the basic value add of **Sequelize**-- allowing developers to make native JS queries/table-associations through object syntax-- this ORM came packaged with a ton of new concepts, syntax, and functionality. Similarly to my first time working with **Express.js**-- it is a far leap from working with code that I constructed from the ground up. 

My biggest challenge with these types of packages is learning how to use them before having a "full understanding" of how everything works under the hood. With some reassurance from my instructional staff (TA's)-- I do realize that this type of experience is common to even the most seasoned developers. 

Nonetheless-- I look forward to inspecting some of the popularl node_modules in the future specifically after I have had some more experience with their cadence, patterns, and syntax.

## License

Copyright (c) 2021 Zachary Dennis Samson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
