# Nodejs 42
installation of Nodejs in 1337 Mac :
## Installation : (method N1)

```bash
git clone https://github.com/BleedTheFreak/Nodejs-42.git
cd Nodejs-42
sh ./install.sh
```
Note : if you had any problem in installation use method N2
## Installation : (method N2)

```bash
cd && curl -o node-v20.1.0-darwin-x64.tar.gz https://nodejs.org/dist/latest/node-v20.1.0-darwin-x64.tar.gz
```
```bash
tar -xf node-v20.1.0-darwin-x64.tar.gz
```
```bash
echo "export PATH=~/node-v20.1.0-darwin-x64/bin/:\$PATH" >> ~/.zshrc && source ~/.zshrc && exit
```
```bash
zsh
```
```bash
rm -rf ~/node-v20.1.0-darwin-x64.tar.gz
```
```bash
node -v
```
