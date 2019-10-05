---
description: We'll be focusing on debian-based distributions. (Ubuntu being the primary.)
---

# Getting Started on Linux

## Installing Node.js

To run anything we need to have `node.js` and `npm` \(node package manager\).

1. Getting `curl` command line interface:

```
$ sudo apt-get install curl
```

    2. We add the Personal Package Archive:

```text
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
```

   3. Installing Node.js:

```text
sudo apt-get install nodejs
```

In order for changes to take effect, you must restart your machine.

{% hint style="info" %}
NPM comes with node, no additional installation is required this way.
{% endhint %}



