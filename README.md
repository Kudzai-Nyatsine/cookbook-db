# Db

This repository is an introduction on how to install Mongodb Cookbook on a project. THe instructions stated below assume you have already installed chef in order to get the peoject running.

## Getting Started

To ensure Mongodb instance is correctly installed in the cookbook, you will need to follow few steps.

Set up your chef command 

	chef generate kitchen [folder name]
Run to create the virtual machine in chef
  	
  	kitchen create 
  	
	
Open your project in the text editor. 

## Installation. 

Clone this repository from [Kudzai's Respository](git@github.com:Kudzai-Nyatsine/cookbook.git).

## Configuration.

Once the text editor is configured, you would need to start off by automation the installation of mongodb in the recipes folder, you will need to;


	kitchen converge  

Run kitchen converge command to converge the instances.


		kitchen verify 
Run kitchen verify to test the instances against the tests created in the default_test.rb


## Licences 

* Author: Kudzai Nyatsine

 


