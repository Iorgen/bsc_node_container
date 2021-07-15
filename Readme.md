
# Start own node 
```shell
docker network create node-access-network
docker-compose up -d --build 
```

# Check status of syncing
docker exec binance-smart-chain-node bsc attach --exec eth.syncing
docker logs -f binance-smart-chain-node
