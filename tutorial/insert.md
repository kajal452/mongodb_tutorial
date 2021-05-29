# Insert Document

MongoDB provides the following methods to insert documents into a collection:

- db.collection.insertOne() 
- db.collection.insertMany()

 if you don't have any collection(table) then mongodb automatically create that collection for you.

```mongodb
    db.users.insertOne({'first_name':'Kajal','last_name':'Das'})
```