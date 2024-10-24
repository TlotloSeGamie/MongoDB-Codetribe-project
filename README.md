# Project Name: Codetribe

## Starting the MongoDB Shell (Mongosh)

Once MongoDB is running, you can start the MongoDB shell (Mongosh) by opening your terminal and typing: mongosh 

Then hit enter button

### 1. **Create Database: `Codetribe`**

In the MongoDB shell, run the following command to switch to (or create) the `Codetribe` database: use Codetribe



### 2. **Create Collections**
#### 2a. Create `Facilitators` Collection and Insert a Document

To create the `Facilitators` collection, run the following command:
db.Facilitators.insertOne({
   Name: "Kabelo Gaotlhaelwe",
   Location: "Kimberley",
   Course: "Full Stack Web Development"
})

This command creates a collection named `Facilitators` and inserts one document into it with the following fields: `Name`, `Location`, and `Course`. 




#### 2b. Create `Trainees` Collection and Insert a Document

Similarly, create the `Trainees` collection and insert a document:

db.Trainees.insertOne({
   Name: "Tlotlo Segami",
   Location: "Kimberly",
   Facilitator: "Kabelo Gaotlhaelwe"
})

This command creates a `Trainees` collection and inserts a document with the fields: `Name`, `Location`, and `Facilitator`.

#### 2c. Create `Projects` Collection and Insert a Document

Create the `Projects` collection by inserting a document into it:

db.Projects.insertOne({
   Name: "MongoDB Project",
   Course: "MongoDB and MongoDB Shell",
   Lesson: "Lesson 1"
})

This command creates a `Projects` collection and inserts a document with the fields: `Name`, `Course`, and `Lesson`.