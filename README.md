# aosc-os-papa-tree
AOSC OS unofficial abbs tree

## Usage
```
curl -o- https://aosc.szclsya.me/papa.asc | sudo apt-key add -
sudo su -c "echo 'deb https://aosc.szclsya.me/papa testing main' > /etc/apt/sources.list" //if you are testing branch user
sudo su -c "echo 'deb https://aosc.szclsya.me/papa stable main' > /etc/apt/sources.list" 
sudo apt update
```
