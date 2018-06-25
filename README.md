Server:
  -> Built using this tutorial: https://blog.risingstack.com/building-a-node-js-app-with-typescript-tutorial

  Running the server:
    -> run: tsc
    -> node --inspect /dist
  
  Testing the server:
    -> run: tsc && mocha dist/**/*.spec.js