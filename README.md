# Scprimec

Network data collector for ScPrime blockchain.
Scprimec is an script that collects key stats of scprime client.
The code is used,changed-modified and adapted for ScPrime blockchain network. 

The original code can be found at: https://github.com/hakkane84/pan-sia

I would like to thank Salva Herrera- he did great statistic for SIA blockchain network.

I would also like to thank Voldemort.


## Requirements
* Node.js installed
* Scprime daemon running to be analyzed 
* Filing instaled 

## Setup

* `npm install` for installing dependencies
* Configure the array and start `daemon` spd --modules="cgehrtw"
* Run with the command `node scprimec.js`

## Web implementation

* Download github repo and copy pweb files to server
*`npm install` for installing dependencies
* Start deamon in 'explorer' mode
* Start node scprimec.js
* Setup Filing to serve local files to external server
