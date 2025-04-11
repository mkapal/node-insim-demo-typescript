# Node InSim Demo Application with TypeScript

A simple demo application using [Node InSim](https://github.com/simbroadcasts/node-insim) to connect to [Live for Speed](https://www.lfs.net/) (LFS).

## Requirements

- [Node.js](https://nodejs.org) 22
- [Live for Speed](https://www.lfs.net/)

## Installation

```shell
npm install
```

## Connecting to LFS

If you want to connect to LFS locally, start LFS and enable InSim by typing `/insim 29999` (or any other port of your choice).

Open the command line and run `npm start`.

This application connects to `127.0.0.1:29999` by default. You can change the host or port by editing [index.js](./index.js).

If you want to connect to a remote LFS host, use the InSim port that is assigned to your LFS host.
