# API
The purpose of the API is to abstract all the back-end calls into a single .js file.

The requirements are the API must be:

1. compatible* with solid long-chat; both in ontology shape and it's data discovery / storage conventions.
2. a single .js in two flavours; one containing all dependancies, and another with only the data api.

*Notes:  when I say compatible,  compatiblity is the first priority, but compatibility will be sacrficed for app scalability / performance, if that is needed.
