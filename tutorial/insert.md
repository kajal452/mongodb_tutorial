# Insert Document

Mongodb provide two method for insert a document if you don't have any collection(table) then mongodb automatically create that 
collection for you.

```mongodb
    db.users.insertOne({'first_name':'Kajal','last_name':'Das'})
```