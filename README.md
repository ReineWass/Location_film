# Location_film
conception de requete

1) Une requete pour ajouter un film ---->
  INSERT INTO infofilms VALUES("idfilm", "nomfilm", "titrefilm", "datesortie", "duree", "realisateur")
  ...VALUES("", "", "","", "", "");
  
  
2) Une requete pour modifier un film -----> UPDATE infofilms SET idfilm ="", titrefilm = "", datesortie = "", duree = "", realisateur = "", WHERE film.idfilm =1;


3) Une requete pour supprimer un film-- --> DELETE FROM infofilms WHERE film.idfilm = 1;
 
 
4) Une requete pour ajouter un client ---->  INSERT INTO Clients("idClients", "noms", "prenoms", "email")  VALUES("", "", "", "");
 
 
5) Une requete pour modifier un client ----> UPDATE Clients  SET  idClients = NULL, noms = "", prenoms= "", email= "", WHERE clients.idclients = 1;
 
 
6) Une requete pour supprimer un client ----> DELETE FROM Clients WHERE Clients.idClients = 1;
 
 
7) Une requete pour afficher les 3 derniers films ajoutés ---->  SELECT * FROM infofilms ORDER BY idfilms  DESC LIMIT 3;
