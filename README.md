# SAVR - Software for State Archive of Vinnytsia Region
Root folder which will contain all code. Microservice architecture will be used

## Ideas for implementation

1. Basic client server approach. Server - java spring boot reactor, client browser website 
2. Web server which will store all documents and provide fast search over them
3. Data will be duplicated, because expected to store original source files and files in DB
4. As storage going to use elastic search
5. Multiple formats of source files will be supported. Word, PDF etc
6. Text should be stored separately from visual representation
7. Server should be able to respond with files in different formats. Default HTML, to show file if search match found
