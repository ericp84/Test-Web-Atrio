# Test-Web-Atrio
1) Retourner tous les éléments book
  //*
  
2) Retourner tous les éléments title ayant comme parent un élément book avec un attribut type égal à roman
  //book/title[@roman]
  
3) Retourner le nombre d'éléments book ayant un attribut type égal à bd 
  count(//book[@bd])

4) Que renvoie la requête XPath suivante :  /library/library/ancestor-or-self::library
    <title>toto1</title> 
    titi 
    <title>toto2</title> 
    titi 
    <title>toto3</title> 
    titi 
    <title>toto4</title> 
    titi2
