const { ethers } = require("ethers");

const eth = "1.5";

const wei = ethers.parseEther(eth);
const convertedETH = ethers.formatEther(wei);

console.log(":", eth);
console.log("Wei:", wei.toString());
console.log("Converted ETH:", convertedETH);
