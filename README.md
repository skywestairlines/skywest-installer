# Overview
This package, 'skywest-installer' is created to easy the process of creating a new skywestairlines repository from the command-line.

## Requirements
To use this command you need to have composer installed on your machine. Instructions are here: https://getcomposer.org/download/

## Installation
At the command prompt type (or just copy and paste the line):

        composer global require skywest/installer dev-master --prefer-source
  
This will install the "skw" command on the composer global space. When prompted follow the instructions to complete.

## Usage
Just type the following command to start the cloning process:
       
       skw

By default, this command will first check if there is a newer version of this install and automatically install it. To skip this processs, you can issue a skip flag to the command to skip updating

        skyw --skip
Or, in short,

        skyw -s

Other flags you can use are:

       -h, or --help            show this page, or a help section for this 'skw' command
       -d. pr --default         run 'skyw' command faster, using all the defaults at each prompt

## Authors
* Hilkiah Makemo                HilkiahMakemo@github.com

## License
Copyright (c) 2018, <copyright holder>
Property of SkyWest Airlines.
