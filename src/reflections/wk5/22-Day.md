# Day 21
__01/12/2020__

## Thoughts on MongoDb Relationships

### What are the three types of relationships?
The three types of relationships are: 1:1, 1:N, and N:M.  These represent One to One, One to Many, Many to Many.

### What are the benefits of the traditional `linking` of relationships instead of `embedding`?
Embedding has the potential to exceed the maximum document size if the embedded array grows too large.  There is also no way to limit the number of returned items when embedded is used. 

### What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
The main factor to take into consideration seems to be the amount of data that will be in the collections. However taking scaleability into consideration then the third collection embedding seems to be the most efficient choice.


#### Afternoon Lab: [Gregslist Server](https://trevor-r-allen.github.io/winter20-gregslist-server/)
####                [Gregslist Server Code](https://github.com/trevor-r-allen/winter20-gregslist-server)