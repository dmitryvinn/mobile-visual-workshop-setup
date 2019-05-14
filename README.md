# Setup Instructions Uphill Battle of Mobile Visual Regression

## Welcome
Welcome to a tutorial on mobile visual testing, aka "Uphill Battle of Mobile Visual Regression". 
This short instruction should help you to get going quickly and help with the basic setup procedures.

**Important:** Make sure to follow installation instructions in order (or at least do the basic once first).

**Note:** Most of the installation steps require ```sudo``` access (in other words, Administrative Access, aka, Root). 
In simple terms, if you are running any installation commands, make sure to run it as ```sudo```.

## Hardware Requirements
Laptop is the only required hardware for this tutorial. You can use any Operating System. 
However, Mac or Linux machines are preferable since it is easier to follow [installation steps](#Installing Basics)

## Installing Basics
We will require next software:
* git
* npm/nodejs
* Firefox

### Installing Git
Git is required to work with source repositories used in this tutorial. 
Follow these instructions to [install git](https://www.linode.com/docs/development/version-control/how-to-install-git-on-linux-mac-and-windows/).

### Installing NPM/NodeJS
NPM is a packaging managers which will help to control dependencies used in this tutorial. 
NodeJS is a Javascript runtime environment which we will use to write some of our tests (and then run them).
NPM is packaged with NodeJS, so if you install NodeJS, you will get both pieces on your workstation.

If you are using **Mac/Linux**, use [this link for installation instructions](https://wsvincent.com/install-node-js-npm-mac/).
If you are using **Windows**, use [this link for installation instructions](https://wsvincent.com/install-node-js-npm-windows/).

### Installing Opera Browser
Opera is a web browser we will use in some of our tests. 
Follow [this link to install](https://www.opera.com/).

## Installing Testing Software
This tutorial uses several tools you will need to install:
* Appium
* BackstopJS
* Jest

### Installing Appium
Appium is what we will use to run automation for mobile devices on your laptop. 
Regardless of your OS, follow [this link to install](https://www.edgewordstraining.co.uk/2017/07/05/install-appium-server-windows/) it on your machine.

### Installing BackstopJS
BackstopJS is an open-source, configuration-driven, visual testing tool. 
To install, [follow this link](https://www.npmjs.com/package/backstopjs).

### Installing Jest
Jest is a Javascript Testing framework we will use for snapshot testing. 
To install, run ```sudo npm install jest --global```


## Installing Development Environment
To use tools described in this tutorial, you will need a few IDEs:

* Intellij IDEA
* Android Studio
* WebStorm Studio
* Visual Studio Code

### Installing Intellij IDEA
As the primary way to write our tests, and run them, we will use Intellij IDEA. 
Go to [this link](https://www.jetbrains.com/idea/download/) to download a community edition.

### Installing Android Studio
Android Studio will help us to run Android Simulator required for automation part of the tutorial.
Follow [these instructions](https://developer.android.com/studio/install) to install Android Studio.

### Installing WebStorm Studio
WebStorm Studio will allow us to easily write Javascript code with a few additional features available in the IDE. 
Install using [this link](https://www.jetbrains.com/webstorm/download).

### Installing Visual Studio Code
As a backup IDE, we will be using Visual Studio Code. 
Install it using [this link](https://code.visualstudio.com/).

## Cloning Repositories
During this tutorial, we will be coding quite a bit. 
Create a folder for the tutorial on your machine, and clone these source to your machine:
* ```git clone -b student https://github.com/dmitryvinn/hello-country-react-live-demo.git```
    * Use Intellij IDEA for this project
    * Make sure to run ```npm install``` after cloning
* ```git clone -b student https://github.com/dmitryvinn/calculator-demo-live.git```
    * Use WebStorm Studio for this project
    * Make sure to run ```npm install``` after cloning
* ```git clone -b student https://github.com/dmitryvinn/hello-country-react-backstopjs.git```
    * Use WebStorm Studio for this project
    * Make sure to run ```npm install``` after cloning
* ```git clone https://github.com/dmitryvinn/hello-country-android.git```
    * Use Android Studio for this project
* ```git clone -b student https://github.com/dmitryvinn/hello-country-webdriver-tests.git```
    * Use Intellij IDEA for this project
