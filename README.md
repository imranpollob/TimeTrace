# TimeTrace
Smart contract time manipulation vulnerability detection tools

## Cloning the project
```bash
git clone --recurse-submodules <repository-url>
```

### Initialize and update submodules
```bash
git submodule update --init --recursive
# pull changes
git pull --recurse-submodules
```


## Submodules
```bash
# add an existing repo as a submodule
git submodule add <repo-url> path/to/submodule
```

Used submodules:
1. https://github.com/imranpollob/slither
2. https://github.com/imranpollob/smart-contract-vulnerability-dataset


## Foundry project
Install foundry
```bash
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

Create proejct
```bash
forge init foundry --no-commit
```