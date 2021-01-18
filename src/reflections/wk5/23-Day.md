# Day 21
__01/13/2020__

## Thoughts on Mongoose: Working with Subdocuments

### In simple terms what is a sub-document?
Simply put, it is a document nested in another document, or a schema nested in anothe schema. MongoDb refers to them as embedded documents.

### When might you use a sub-document?
Perhaps when using the embedding methods to create MongoDb relationships. Or when wanting to keep track of the subdocuments from different schema instances in a single MongoDb collection.

### How do you add to a collection of sub-documnets? What about editing them?
Adding to a collection of subdocuments is as simple as using dot notation to target the subdocument in the schema and using a push method.  Editing is done similarly by assigning the new value to the subdocument via dot notation.


#### Afternoon Lab: [Planets Server](https://tallen-planets-server.herokuapp.com)
####                [Planets Server Code](https://github.com/trevor-r-allen/planets-server)
####                [Planets Server Outline](https://lucid.app/lucidchart/cc2d23a6-0fd1-4a97-bf74-f204b31c15b7/edit?beaconFlowId=A3491929DD85391E&page=0_0#)