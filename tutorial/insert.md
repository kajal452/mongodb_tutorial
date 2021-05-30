# Insert Document

MongoDB provides the following methods to insert documents into a collection:

- db.collection.insertOne() 
- db.collection.insertMany()

 if you don't have any collection(table) then mongodb automatically create that collection for you.

```mongodb
    db.users.insertOne({'first_name':'Kajal','last_name':'Das'})
```


There are another method too from where we can insert document
db.collection.update() when used with the upsert: true option.
db.collection.updateOne() when used with the upsert: true option.
db.collection.updateMany() when used with the upsert: true option.
db.collection.findAndModify() when used with the upsert: true option.
db.collection.findOneAndUpdate() when used with the upsert: true option.
db.collection.findOneAndReplace() when used with the upsert: true option.
db.collection.save().
db.collection.bulkWrite().