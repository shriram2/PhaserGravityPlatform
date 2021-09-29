# PhaserGravityPlatform
## Table of contents
* [General info](#Getting started in Phaser with basic physics in Phaser)
* [Technologies](#Phaser HTML 5)
* [Setup](# No setup needed Just download the files)

## General info
This project is simple HTML5
	
## Technologies
Project is created with:
* HTML5
* Javascript 
* Phaser 5
	
## Setup
To run this project, install download files in a directory and then click the html files
* The assets can be placed in asset folder
* Enable the Chrome server
* Make the chrome server point to the folder of the main project 
* The basic idea here is show the simple physics. 
* https://phaser.io/tutorials/making-your-first-phaser-3-game is the main reference. 
* We can see the gravity effect. Addition of a collider in a platform. 
* We can see the difference between global gravity setting and the setting on a local scale an object alone. 
* physics: {
        default: 'arcade',
        arcade: {
         //gravity: { y: 300 },
            debug: false
        }
    },
* If the gravity is not commented, gravity is applied globally
* player1.body.setGravityY(20);  shows local gravity setting
* The following code show the staticGroup formation
* platforms = this.physics.add.staticGroup();
* platforms.create(600, 400, 'ground');
* 
* 
* the static physics is also shown
* 
* 

