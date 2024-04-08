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
![graph](https://github.com/DamanAhuja/Security-Audit/assets/142963733/8a3a2ea4-0ffd-44d0-892f-33e8d16bd23a)
## Slither
![image](https://github.com/DamanAhuja/Security-Audit/assets/142963733/646e473d-f291-460e-9072-243be21ade7b)
![image](https://github.com/DamanAhuja/Security-Audit/assets/142963733/6fcd5d51-03ee-49b3-ae48-02c14dfdf1cb)

