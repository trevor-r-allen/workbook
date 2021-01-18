# Day 21
__01/14/2020__

## Thoughts on Virtuals in Mongoose

### What is a virtual property?
Additional fields on a model that exist logically and not literally in the collection.

### When might you use a virtual property?
When you forsee repeatedly concatenating values from the data.  Or to limit the additon of extra properties to the models that would consist of repeated data but in a different format.

### How do you search by a virtual properties value?
You can't search by a virtual properties value. The virtual property doesn't exist in the database/collection.


#### Afternoon Lab: Hackathon prep