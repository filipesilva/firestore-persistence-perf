# firestore-persistence-perf

Benchmarking setup to measure the difference that enabling persistence has on Firestore, as part of https://github.com/firebase/firebase-js-sdk/issues/2457.

```
git clone https://github.com/filipesilva/firestore-persistence-perf
cd firestore-persistence-perf
yarn
yarn emulators
```

Go to http://localhost:5000/ and you can see the average time per write and total time in the console.