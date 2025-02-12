# netskope-test

run `yarn install --check-cache` with Netskope ON to install the dependencies

get the error

```
➤ YN0000: ┌ Fetch step
➤ YN0001: │ RequestError: self-signed certificate in certificate chain
    at ClientRequest.<anonymous> (/Users/nicolas.challeil/.cache/node/corepack/v1/yarn/3.2.0/yarn.js:195:14361)
    at Object.onceWrapper (node:events:633:26)
    at ClientRequest.emit (node:events:530:35)
    at o.emit (/Users/nicolas.challeil/.cache/node/corepack/v1/yarn/3.2.0/yarn.js:190:90444)
    at emitErrorEvent (node:_http_client:103:11)
    at TLSSocket.socketErrorListener (node:_http_client:506:5)
    at TLSSocket.emit (node:events:518:28)
    at emitErrorNT (node:internal/streams/destroy:170:8)
    at emitErrorCloseNT (node:internal/streams/destroy:129:3)
    at process.processTicksAndRejections (node:internal/process/task_queues:90:21)
    at TLSSocket.onConnectSecure (node:_tls_wrap:1679:34)
    at TLSSocket.emit (node:events:518:28)
    at TLSSocket._finishInit (node:_tls_wrap:1078:8)
    at ssl.onhandshakedone (node:_tls_wrap:864:12)
```
