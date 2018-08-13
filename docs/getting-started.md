---
id: getting-started
title: Getting started
---

Aragon is a project to empower freedom by making decentralized governance happen.
We have built multiple pieces of infrastructure to make this happen:

- **aragonOS**: A framework that enables flexible and upgradeable governance mechanisms by creating and assigning permissions to multiple entities.
- **aragon.js**: A Javascript library to interact with aragonOS by handling transaction pathing, upgradeability and state of the contracts.
- **Aragon UI**: An Aragon-native toolkit of UI components for decentralized apps.
- **Aragon Core** ([try it out](http://app.aragon.one)): A client to interact with aragonOS-powered decentralized organizations. It implements a signer with transaction pathing, notifications and a sandboxed environment for aragonOS-based apps using aragon.js.

Although these components are very powerful together, you can use them indivually.
We will explore how to do both.

=-=-=-=-=-=-=-

What you need to get started building with Aragon.

- [Goals of Aragon](#goals-of-aragon)
- [Environment setup](#environment-setup)
- [Quick start](#quick-start)
- [Next](#next)

## Goals of Aragon

**What are DAOs?**

DAOs allow us to have organizations that live on the blockchain, allowing for features such as censorship resistance, decentralization and transparency. If you want to know more about DAOs checkout [link](https://en.wikipedia.org/wiki/Decentralized_autonomous_organization) and [link](https://blog.ethereum.org/2014/05/06/daos-dacs-das-and-more-an-incomplete-terminology-guide/).

**What can we do with them?**

Aragon DAOs are super easy to create. All you have to do is enter a few details and pay the gas fee. Once you have a DAO you can begin inviting members to start participating within your organization including but not limited to: creating governance models, voting on issues, setting up payroll and polling the community.
Lets jump into building our first DAO

##Environment setup

**Node version**

Make sure you have at least Node >= 8.0.

**Metamask**

We recommend using the Metamask browser extentsion(https://metamask.io/) to send transaction to the blockchain.

**Install the Aragon CLI**

From the command line run:

```bash
npm i -g @aragon/cli
```

Once we have this package installed we can start building DAOs from the command line.

**Quick start**

To create your first DAO run:

```bash
aragon init foo.aragonpm.eth
```

Congrats you have just created a DAO! It’s running on your local network and you can check it out by going to localhost:3001

**Next**

Now that you’ve built a DAO let's take a look at the docs to learn the docs or you can jump into the tutorials.
