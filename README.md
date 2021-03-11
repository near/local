# local

* wallet
* near-contract-helper
* indexer

Requirements:
docker and docker-compose

Starting all applications

```bash
docker-compose up
```

Stopping

```bash
docker-compose down
```

Running commands inside containers

```bash
docker-compose exec bridge head /root/.rainbow/logs/ganache/out.log -n 20
```

Default urls:

near-wallet: http://localhost:1234
bridge-frontend: http://localhost:2000
explorer: http://localhost:9001
