# Location_film
conception de requete

 Une requete pour ajouter un film ---->
  INSERT INTO films VALUES("idfilms", "nomfilm", "titrefilm", "datesortie", "duree", "realisateur")
  ...VALUES("", "", "","", "", "");
  
  
 Une requete pour modifier un film -----> UPDATE film SET idfilm ="", titrefilm = "", datesortie = "", duree = "", realisateur = "", WHERE film.idfilm =1;


 Une requete pour supprimer un film-- --> DELETE FROM film WHERE film.idfilm = 1;
 
 
 Une requete pour ajouter un client ---->  INSERT INTO clients("idClients", "noms", "prenoms", "email")  VALUES("", "", "", "");
 
 
 Une requete pour modifier un client ----> UPDATE clients  SET  idClients = NULL, noms = "", prenoms= "", email= "", WHERE clients.idclients = 1;
 
 
 Une requete pour supprimer un client ----> DELETE FROM Clients WHERE Clients.idClients = 1;
 
 
 Une requete pour afficher les 3 derniers films ajoutés ---->  SELECT * FROM films ORDER BY idfilms  DESC LIMIT 3;
