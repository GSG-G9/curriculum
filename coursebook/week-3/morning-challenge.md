**Author**: [@besarthoxhaj](https://github.com/besarthoxhaj)  

**Maintainer**: TBC
## Parallel Functions Morning Challenge

When making API calls, exactly how quickly you receive a response can depend on the speed of your connection, connection latency, and the performance of the API that you're calling.
When making several API calls, or reading data from several files at the same time, the order in which each task is completed will depend on how quickly the response/data can be retrieved/extracted, which may not always be the same order that the tasks were called.

Parallel functions can help to run several tasks at the same time, and return the values of those tasks in the order they were called.

Below is an array of functions (the ```tasks``` array), each one set to run at different delays (kind of like the delays you might experience when retrieving data form an API).

Complete the 'parallel' function. It should fire all the tasks at the same time, and invoke the final callback when they are all done.

In case of an error, the final callback should be fired immediately.

The callback accepts two arguments which are error and an array of task results.

TIP: You might want to use [Repl.it](https://repl.it/languages/javascript) to complete this challenge so you can see whats happening in your code.

While you're working on this, think about when this function might be useful (in the context of what you've been studying this week).

More info:
http://caolan.github.io/async/docs.html#parallel
https://brandonwamboldt.ca/asynchronous-javascript-with-callbacks-1769/


```js

function parallel (tasks, callback) {
  // write your code here
}

var timeStarted = Date.now();
parallel([
  function(callback) {
    setTimeout(function() {
      callback(undefined,1);
    },2000);
  },
  function(callback) {
    setTimeout(function() {
      callback(undefined,2);
    },1000);
  },
  function(callback) {
    setTimeout(function() {
      callback(undefined,3);
    },1500);
  },
  // function(callback) {
  //   setTimeout(function() {
  //     callback('boom',undefined);
  //   },1200);
  // }
], function(err,result) {
  var duration = (Date.now() - timeStarted);
  console.log('duration:',duration); // 2000s
  if (err) {
    console.log('err',err); // undefined
  } else {
    console.log('result',result); // [1,2,3]
  }
});
