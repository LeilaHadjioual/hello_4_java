# hello_4_java


**mvn compile**  
  
    compile les sources (lancée depuis le répertoire racine de l'application)
    crée le dossier target
    compile les fichiers .java en .class (code binaire) dans le dossier target 
  

**mvn install**

    crée le fichier .jar (qui comprend tous les fichiers.class)
  

**java -cp target/hello-1.jar hello.HelloWorld**  

    exécute le programme et l'affiche 
    cp : chemin où est le fichier
    hello.HelloWorld : pointe la classe à exécuter (classe HelloWorld dans fichier hello)


----

### Autre commande :   

**mvn clean**

    permet d'effacer tous les fichiers générés pendant les exécutions précédentes
