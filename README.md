# Kusama Blockchain 

[Kusama](https://kusama.network/) is a canary Polkadot's network. It's a scalable, multichain network for radical innovation. Kusama serves as a proving ground that allows teams and developers to build and deploy a parachain, and experiment with Polkadot’s governance and NPoS functionality in a real environment.


## Overview

This repository contains the dockerized Kusama blockchain node. I was able to dockerized the blockchain node, run, and tested after allowing the node to synced fully. Interacted with the node using some [JSON-RPC](https://polkadot.js.org/docs/substrate/rpc) commands and [Polkadot's API](https://polkadot.js.org/docs/api). 


## Usage 
- Install [docker](https://docs.docker.com/get-docker/)
- Check if your docker is running, if not start it. 
- Clone the repository
- Cd into the cloned project using your terminal and run the docker command below:

    ```shell
    docker-compose up
    ```

