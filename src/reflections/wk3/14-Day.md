# Day 14
__12/17/2020__

## Thoughts on The Observer Pattern

### What problems does the observer patter seek to solve?
The need to update the DOM with data as it is changed by events and inputs. Keeping many elements in sync.

### What are the three mechanisms of the observer pattern?
The three mechanisms are subscribe, unsubscribe, and brodcast. Subscribe and unsubscribe add and remove events to the observers array while brodcast injects data into those observers.

### Review the code from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the 'magic' of the bcw-template uses these two concepts to manage and update the DOM.
When we create the proxy state object it is embedded with the emit function. Later using the proxystate.on method we then can specify the function to run and store the specified object in the _listeners dictionary with its variable name as the property. When the proxy state object is changed the embedded emit method is triggered. This emits the variable name to be compared to the properties in _listeners and if its there it runs the function that was passed with proxystate.on

#### Team Afternoon Lab: [Online Shop](lablinhttps://trevor-r-allen.github.io/mvcs-online-shop/k)
