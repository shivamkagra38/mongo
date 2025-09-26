## Commands of MongoDB shell

# Simple operations
 - Show dbs -> Show all the databases of cluster
 - use _database_ -> switch to _database_

# Create operations
 - **first run use _database_ command to switch to database where create operation is to be executed**
 - db.collectionName.insertOne( {"name":"abc", "role":"SDE"} )
 - db.collectionsName.insertMany( [{"name":"abc", "role":"SDE"}, {"name":"xyz", "role":"qwe"}, {"name":"hyu", "role":"tyu"}] )