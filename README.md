# meraki-node-red

A collection of Node-RED flows to demonstrate Meraki API solutions.

## Usage
The repository contains flow files with a `.json` extension. 

You can download the file and then run `node-red filename.json` to launch Node-RED with the application file.

Alternatively, copy the contents of the `json` file and paste it into the Node-RED editor via the **Import** option, then paste from **Clipboard**
 

## Installation

### Install MongoDB 
*(used as the database for various sample flows)*

https://docs.mongodb.com/manual/installation/

### Install Node-RED
https://nodered.org/docs/getting-started/installation

In addition, there are several extra nodes that are required for the flows to work. Here is a listing of the additional nodes.

- node-red-node-mongodb
- node-red-contrib-mongodb2
- node-red-contrib-meraki-cmx
- node-red-contrib-spark

```
cd ~
cd .node-red
npm install node-red-node-mongodb node-red-contrib-mongodb2 node-red-contrib-meraki-cmx node-red-contrib-spark

#start node-red
node-red
```


## More information and installation instructions
* Node-RED: https://nodered.org/



*examples written by Cory Guynn*
2017
