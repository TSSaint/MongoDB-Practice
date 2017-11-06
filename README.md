# MongoDB-Practice

This repository is a dive into MongoDB and MongoDB Compass.

# UNIT 1
## MongoDB Compass:
A powerful GUI for MongoDB interactions/querying where you can even specify and visually manipulate data.
The course will make extensive use of MongoDB Compass.

### Main
Shows databases in the cluster

### Database
A namespace for collections. Databases can contain many collections.

## Collections
Store individual records called “documents”. In collections, we store grouped data that is used within single applications.

Each DB and Collection combination references a “namespace” using dot notation:

Ex. City.neighborhoods

Name -> Size -> Collections -> Indexes

## Compass Schema
Allows you to see a large-scale macro view of all data inside the database/collections. You have the ability to see a large overview of the kinds of datatypes that exist in the document.

Nested Documents
Schema can show that there are documents with multiple documents inside!

Documents = Objects!

As is evidenced by the Compass user interface, MongoDB provides specific support for documents, arrays, and geospatial data.

Geospatial Data
MongoDB has native support for common data structures regarding geospatial data!

# JSON
JavaScript Object Notation format is what is used to define filters. They are typically arranged in:
{key:pair}
ex. {“shoes”:{“blue”,”red”,”yellow”}}

Operators
In MongoDB, these operate with selectors "$", for example, in $key:val pairs. These select specific start/endpoints of data, or even work similarly to functions!
$(somestring)
ex. {“fruits”:{“$A”:”Apple”,”$B”:”Banana”,”$C”:”Cranberry”}}

JSON in Depth
LEARN MORE: http://www.json.org/
A popular format for representing formats.

We typically use JSON document/object to refer to specific data structures. Each begin with curly braces, and each have a key:val pair. Key:val must be separated by colons. Objects/documents can be nested in other documents, be empty, or even contain arrays inside. Strings must be defined within dual quotes. Whitespace is insignificant in JSON.

JSON support any kind of hierarchy appropriate to most applications’ data models.

Some datatypes:
String, Int, Float, Bool, Object, Array, Whitespace
_____________________________________________________
