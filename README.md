<h1 align="center">🔧 FiveM TypeScript Resource Boilerplate</h1>

This repository is a basic boilerplate for getting started
with TypeScript resources in FiveM. 

## Requirements
* Node > v14
* Yarn

## Getting Started

**Install Dependencies**

Navigate into the newly cloned folder and execute
the following command, to install dependencies.

```sh
yarn install
```

## Development

### Hot Building

While developing your resource, this boilerplate offers 
a `watch`script that will automatically hot rebuild on any
change within the `client` or `server` directories.

```sh
yarn watch
```
*This script still requires you restart the resource for the
changes to be reflected in-game*

### Entry Points
**Client** - `./client/index.ts`

**Server** - `./server/index.ts`

## Production Build
Once you have completed the development phase of your resource,
you must create an optimized & minimized production build, using
the `build` script.

```sh
yarn build
```