# WILDLIFE TRACKER
#### A web app for cataloging animals spotted.
#### By **Denning Kevin Mulama**

## Description
This is a web app which enables a user to input an animal he or she has identified.

## Setup/Installation Requirements
* To use this project, clone it.
* Make sure java, gradle, heroku and postgresql is installed
* Open the project in the IDE and push to heroku master, then open the link provided in the terminal
* In PSQL:
  CREATE DATABASE wildlife_tracker;
  CREATE TABLE animals (id serial PRIMARY KEY, name varchar,health varchar,age varchar);
  CREATE TABLE sightings (id serial PRIMARY KEY, location varchar,rangername varchar,animalid varchar);

## Technologies Used
Java
Heroku
Postgresql

##Live Link
https://spotter-reporter.herokuapp.com/


## Support and contact details
Contact +254791062106 for any questions concerning the app. Feel free to give your feedback too.
### License
* MIT License

Copyright (c) 2019 Denning Kevin Mulama

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

Copyright (c) 2019 **Denning Kevin Mulama**
