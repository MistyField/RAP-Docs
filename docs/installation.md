---
hide:
  - navigation
---

# Installation

!!! info "🔧 For client"

    The client does not need to install any program, please 
    visit [http://54.169.242.254:5000](http://54.169.242.254:5000/buildReactions)!


## Install with docker(recommended)

Since the installation process requires docker, please install [docker](https://www.docker.com/) first.

## Install with source code

This project requires the use of docker and yarn for deployment, so please install [docker](https://www.docker.com/) and [node.js](https://nodejs.org/en) with [yarn](https://yarnpkg.com/) first!

```shell
git clone https://gitlab.igem.org/2023/software-tools/fudan
# compile webUI
cd fudan/webUI
yarn install
cd ../
sh pack.sh
docker compose up -d
```

After that RAP will be running at http://127.0.0.1:5000.