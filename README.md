#Better Testing of Microservices Using Consumer-Driven Contracts in Node.js
========

### Accompanying blog post [here](http://hecodes.com/2016/10/better-testing-microservices-using-consumer-driven-contracts-node-js/)

## Installation
Clone repository and run

```
npm install
```

## Usage
Run consumer-side tests

```
mocha app/client/spec/PostServiceClient.spec.js
```

Run provider-side tests

```
node app/service/spec/PostService.spec.js
```


curl -X DELETE -u 'sSR6cB6Jt8UE8dyx5pc5QD7V8x2Of:krnrmVVeYYDEMmjeysh8r8GoK0iktOm' https://elabor8.pact.dius.com.au/pacticipants/My%20Consumer
