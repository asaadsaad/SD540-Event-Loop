## SD540-Event-Loop
### Update the `README.md` file, to include the answers to the following questions:
1. Explain the difference between `setImmediate(f)` and `setTimeout(f, Time)`? 
2. Explain the difference between `process.nextTick(f)` and `setImmediate(f)`?
3. Explain the difference between `process.nextTick(f)` and `queueMicrotask(f)`?
4. Name 10 of Node Core modules
5. Name 10 of Node Global objects
  
#### Navigate to `test` folder, run `npm i`
Write down your observation and explain what happens in Node when you run the following commands:
   * `npm run start`  
   * For Windows: `SET UV_THREADPOOL_SIZE=2 && npm run start`.
   * For MacOS: `export UV_THREADPOOL_SIZE=2 && npm run start`
