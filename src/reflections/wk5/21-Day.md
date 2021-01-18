# Day 21
__01/11/2020__

## Thoughts on Using Query Parameters

### What is the purpose of a query string?
To pass additional data into a request. It can then be captured from the request object and used.

### What is the format of a query parameter? How does it start? How do you distinguish between one parameter and the next?
To use a query parameter, merely append the URL with a question mark followed by the key/value pairs separated by ampersands.  For example, `http://website.com/api/endpoint?key1=value1&key2=value2`

### When do you think query parameters would be helpful when writing your server?
Queries would be useful when handling a `get` request and can be passed in order to filter the results appropriately.

#### Afternoon Lab: [Burgershack](https://trevor-r-allen.github.io/burgershack-node/)
####                [Burgershack Code](https://github.com/trevor-r-allen/burgershack-node)