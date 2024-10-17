# Mongo-DB-shell-commands
## Commands to run to create a database in mongo DB
## Open terminal or command prompt
To ensure you have installed mongodb and mongo shell
- "type" mongod --version
# To run
- "type" mongosh
- A connection of mongoDB and mongo shell will be shown
# To view Database found in mongo
- "type" show dbs
# To create a Database
- "type" use Codetribe
- This will create a database "named" Codetribe if not available, when available use it
- You will be redirected to the database/collection "named" Codetribe
# To insert data/document into the database/collection
- db.Facilitator.insertOne({name:"Mahaltse", Location:"Soweto", Course:"Web Development"})
- db.Trainees.insertOne({name:"Edward", Location:"Soweto", Faciliatator:"Mahlatse"})
- db.Projects.insertOne({name:"MongoDB", Course:"Web dev", Lesson:3})
- This creates a collection with a document with data
# To view the collection
- "type" show collections


__________________________
![image](https://github.com/user-attachments/assets/1861975f-3d01-4a8f-8c01-809532f58cc9)
