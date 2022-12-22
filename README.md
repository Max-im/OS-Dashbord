# Dashboard

## Description

Dashboard to display computer performance.
Shows your OS info.
Server watches clients and nodeClients joining and changes computer performance visualization.

## Tech

- React
- Redis
- MongoDB
- NodeJS
- Socket.io
- Workers
- Sticky Session

## Install

1. install server `cd server` and `npm i`;
2. install client `cd client` and `npm i`
3. install client `cd nodeClient` and `npm i`

## Run

1. run redis `redis-server`;
2. make sure mongoDB server run and there is `perfData` database;
3. run server `cd server` and `npm start`;
4. run client `cd client` and `npm start`
5. open browser on `localhost:3000`;
6. run as much nodeClients as you want `cd nodeClient` and `npm start`;
