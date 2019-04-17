MACHINE SIMULATOR
=================

Getting started
---------------

### Windows

* Install Node.js (https://nodejs.org/en/download/)
* Install Git (https://git-scm.com/downloads)

### Linux

Install Node.js:
* `sudo apt-get install nodejs`
* `sudo apt-get install npm`

### Install Machine-Simulator

```
git clone https://github.com/thfrei/machine-simulator
cd machine-simulator
npm install
npm start
```

Connect with UAExpert
---------------------

`opc.tcp://localhost:4334`

Usage
---------

* Set Amount = 4
* Set State = 1 (PRODUCING)
* Wait
* State will change to 0, indicating NOT PRODUCING
* Amount will change to 0
* Produced Amount will change to 4
