---
author:
  name: Jared Kobos
  email: docs@linode.com
description: 'Install up to date versions of Node.js with an Ubuntu PPA'
keywords: []
license: '[CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0)'
published: 2018-03-06
modified: 2018-03-06
modified_by:
  name: Linode
title: 'Install Node.js using an Ubuntu ppa'
shortguide: true
---

1.  Use `curl` to download the setup script provided by NodeSource. Replace the Node version in the `curl` command with the [version you would like to install](https://github.com/nodesource/distributions/tree/master/deb):

        curl -sL https://deb.nodesource.com/setup_9.x -o nodesource_setup.sh

2.  Run the script:

        sudo bash nodesource_setup.sh

3.  Update package lists:

        sudo apt update

4.  Install Node.js:

        sudo apt install nodejs

The Node Package Manager (NPM) will be installed alongside Node.js.
