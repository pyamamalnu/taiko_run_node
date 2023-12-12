# taiko_run_node

## Prerequisites

Docker is installed and running.
Git is installed.
If using Windows, you should install Git BASH or WSL to use as your terminal.
Meet the Geth minimum hardware requirements except for the storage requirement because Taiko nodes will require less storage. As of 2023-09-18 a node uses less than 10 GB. 100 GB should be future proof enough if you intend to run your node for a while.

# 1

Clone simple-taiko-node

```
git clone https://github.com/taikoxyz/simple-taiko-node.git
```
```
cd simple-taiko-node
```


# 2

```
cp .env.sample .env
```
