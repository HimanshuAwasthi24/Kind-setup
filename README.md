### Installation of kind , Creating on prem clusters on Linux


## Command to install and setup kind with 1 worker and 1 master node

# Lets setup kind fisrt run the following commands one by one

`[ $(uname -m) = x86_64 ] && curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.24.0/kind-linux-amd64`
`chmod +x ./kind`
`sudo mv ./kind /usr/local/bin/kind`

# Let's create cluster
**note:** _copy the config.yml from repo and create your own config.yml of your own configuration_

# Run The following command
`kind create cluster --config config.yml`

**note:** _config.yml is the file that you copied from the repo_

