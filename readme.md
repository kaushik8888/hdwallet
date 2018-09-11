# bitimulate

> This service is now available at https://bitimulate.com/

## About

Bitimulate is compound word of **Bit**coin and S**imulate**. This service provides a simulated cryptocurrency trading system. Data used in this service rely on realtime information at [Poloniex](https://poloniex.com).

Currently, Korean is the only supported language in this service. English, and other languages might be implemented later on...

## Stack

Everything in this project is in JavaScript. 

### Frontend

- react
- react-router
- redux
- CSS Module + Sass
- [Atomic React Component (ARc)](https://arc.js.org)
- EChart

### Server

- Node.js
- Koa
- MongoDB (mongoose)
- Redis
- Websocket

#### AWS
- EC2
- S3
- Cloudfront
- ElasticLoadbalancer

## Running on your Machine

These instructions will get you a copy of the project up and running on your local machine for development or testing purposes.

### Prerequisites
- Node.js v8^
- yarn
- MongoDB
- Redis

### Installation
Clone this project from the github repository.

```bash
$ git clone https://github.com/velopert/bitimulate