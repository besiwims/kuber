Kuber
===========

Haskell library and API server for composing balanced Cardano transactions.

[KuberIDE.com](https://kuberide.com) is Oficial IDE and plutus development and trying out kuber-server features.

OpenSource Kuber playground is [here](https://dquadrant.github.io/kuber-playgrounnd/)


## Docs
 - [JSON API](https://kuberide.com/kuber/docs/intro)
 - [Kuber Haskel Library](https://dquadrant.github.io/kuber)

## Example Project using Kuber (v2)
[cardano-marketplace](https://github.com/dQuadrant/cardano-marketplace)


# Run Kuber-Server with docker-compose

Kuber can be stared easily with [docker-compose.yml](./docker-compose.yml) file. But you will have to wait for cardano-node to sync to latest block

```bash
git clone https://github.com/dquadrant/kuber.git
git checkout 3.0.0-rc1
docker-compose up -d
```


If you want to build docker image locally, you can use the helper script
```bash
$ ./.ci/build
```

## Developer guide
Instructions for local development of kuber is available in [DEVELOPER.md](DEVELOPER.md) 
