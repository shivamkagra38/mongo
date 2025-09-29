### Commands of MongoDB shell

# Simple operations
 - Show dbs -> Show all the databases of cluster
 - use _database_ -> switch to _database_

# Create operations
 - **first run use _database_ command to switch to database where create operation is to be executed**
 - db.collectionName.insertOne( {"name":"abc", "role":"SDE"} )
 - db.collectionsName.insertMany( [{"name":"abc", "role":"SDE"}, {"name":"xyz", "role":"qwe"} ] )

# Read operations
 - **first run use _database_ command to switch to database where read operation is to be executed**
 - db.collectionName.find() -> Fetches all the data of _collection_
 - db.collectionName.find({"name":"Shivam"}) -> Fetches all the data of _collection_ where name is Shivam
 - db.collectionName.find().limit(1) -> Fetches only one document(object)
 - db.collectionName.find().skip(1) -> skips 1st document/object and returns all other documents
 - db.collectionName.find().sort(qty:1) -> Ascending order
 - db.collectionName.find().sort(qty:-1) -> descending order