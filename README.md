# Ganache-Server

## Setup
1. Install docker and git

## Build
1. Clone the repository
   
   ```bash
   git clone https://github.com/chitranjan-gupta/Ganache-Server
   ```
2. cd into the directory
   ```bash
   cd Ganache-Server
   ```
3. Build the Docker Image
   ```bash
   docker build --file Dockerfile ganache-server .
   ```
## Execute
1. Run the docker image
   
   ```bash
   docker run -it -p 8545:8545 ganache-server
   ```
## Account 
> Test account private key is present in custom-accounts.json

> If you want add account or remove account edit Dockerfile

Sources:
1. https://github.com/trufflesuite/ganache
