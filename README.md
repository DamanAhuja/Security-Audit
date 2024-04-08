# Security-Audit
## SolGraph
### Image Pull 
```
docker pull devopstestlab/solgraph
```
### Directory
First of all we have to create a directory
```
mkdir <"dir name">
```
then enter the newly made directory
```
cd <"dir name">
```
Then we have to create a MyContract File
```
touch MyContract.sol
```
Edit this file and Enter the MyContract.sol contents
### Run Solgraph
```
docker run -it --rm -v $PWD:/data devopstestlab/solgraph
```
It will return output as your files name i.e. MyContract.sol

Now the graph is generated succesfully, To view it -
```
xdg-open MyContract.sol.png
```
