
# Start own node 

Copy whole project to server
create node directory in bsc_node_container dir
give chmod to node for volume accessibility

compile geth from source 
push geth executable to src folder under geth name 


```shell

docker network create node-access-network
docker-compose up -d --build 
```

# Check status of syncing
docker exec binance-smart-chain-node bsc attach --exec eth.syncing
docker logs -f binance-smart-chain-node


# Start new update status
download 
wget 
unzip 
create node dir
