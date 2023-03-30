General docu for local run: https://github.com/0xPolygonHermez/zkevm-node/blob/develop/docs/running_local.md

1. `docker build -t zkevm-node .` in root dir
2. `cd test`
3. `make run`

For Blockscout repository: 
1. `git clone git@github.com:0xPolygonHermez/blockscout.git`
2. `cd blockscout`
3. `make build-prod`
4. `docker tag hermeznetwork/zkevm-explorer hermeznetwork/hermez-node-blockscout`

Back in zkevm-node repo: 
1. `make run-explorer`
2. `make send-transfers`