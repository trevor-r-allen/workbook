# Day 13
__12/16/2020__

## Thoughts on JS Proxy Objects

### What are the two common operations that we will set in the handler?
'Get' which is usedwhen accessing a key's value. 'Set' which is used when assigning a value to a key.

### What do you have to make sure you are doing with every 'Get' to insure the value does not become 'undefined'?
We have to make sure a value is returned in the handler. For example, the property of the object being passed.

### What are some of the benefits of the proxy object that we are using in our structure for applications?
In the MVCS structure, proxys are used to 'listen' for changes/updates to specified data, allowing us to draw/update the DOM live with the new data.

#### Afternoon Lab: [GregsList2.0](https://trevor-r-allen.github.io/winter2020-mvc-gregslist/)
