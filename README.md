
## Build Process

- Follow the [Docker](https://docs.docker.com/get-docker/) to install Docker.<br><br>
- <b>To pull down the image:</b><br>
`docker run –rm –interactive –tty stackchain/alonzopurple:1.0.1` <br><br>
- <b>To run the node</b><br>
`cardano-node run \`<br>
`–topology /home/cardano-my-node/alonzo-purple-topology.json \`<br>
`–database-path /home/cardano-my-node/db \`<br>
`–socket-path /home/cardano-my-node/db/socket \`<br>
`–host-addr 0.0.0.0 \`<br>
`–port 6000 \`<br>
`–config /home/cardano-my-node/alonzo-purple-config.json` <br><br>
<b>Open a new terminal</b><br><br>
- <b>Connect to the container in a new shell.</b><br>
`docker exec -it  <container> bash`


- <b>Run gLiveView.sh to see the node information</b><br>
`./gLiveView.sh`


