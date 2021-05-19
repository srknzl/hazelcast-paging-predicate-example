# hazelcast-paging-predicate-example

1. Download hazelcast. Extract it somewhere. 
1. Compile and put java classes inside bin/user-lib(In order to compile I use a java project that includes hazelcast as dependency, I suggest to use an IDE like Intellij. Just open the IDE and press build button, then the classes will be in target folder. I included the java project in main folder)
1. Add identified data serializable to bin/hazelcast.xml config(I added hazelcast.xml you can copy it or just copy related part in serialization config)
1. Run hazelcast with bin/start.sh(chmod +x bin/start.sh if not executable)
1. Run the sample code in main.js  
