#level2riak

A network service that allows you to connect to a riak db as if it were a multilevel (levelup) database.

## Install

```sh
npm install -g level2riak
```

## Usage
    
```sh
level2riak --host 127.0.0.1 --port 8087 --listen 8091 --bucket somebucket
```

## Connecting

You can use any leveldb/[levelup](https://github.com/level/levelup) tool to connect to your riak bucket on the listen port.

If you're doing this in your code, you might consider using [riakdown](https://github.com/nlf/riakdown) directly.

One of the great things about this is that it allows you to use level debugging tools like [lev](https://github.com/hij1nx/lev) with Riak.
