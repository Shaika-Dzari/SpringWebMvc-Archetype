SpringWebMvc-Archetype
======================

Spring Web MVC project archetype for maven

# Cloning and installing the archetype
git clone https://github.com/Shaika-Dzari/SpringWebMvc-Archetype.git  
cd SpringWebMvc-Archetype  
mvn install  
  
# Creating a java project
cd /your/workspace  
mkdir YourProjectName  
cd YourProjectName  
mvn archetype:generate -DarchetypeCatalog=local  
  
# Run your project
cd YourProjectName  
mvn jetty:run  
