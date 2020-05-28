## Setup

### Install required software
* [Node.js](https://nodejs.org/en/) (v12.17.0+) LTS

### Setup config file

In Gruntfile.js introduce your username/password for screeps.

### Install npm modules

$ npm install


## Usage

* `grunt main`: Writes your distribution file to the MMO Server
* `grunt sandbox`: Writes your distribution file to the atanner sandbox or another community server
* `grunt merge`: Merges the source files into the dist
* `grunt`: Checks the jshint rules, merges your src files and writes the dist to the remote
