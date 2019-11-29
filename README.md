### GITFLOW initiation

Pour pouvoir utiliser git flow sur nos projets (macOS)

	$ brew install git-flow-avh

on initialise GITFLOW
création de la branch develop et on se place dessus

	$ git flow init
	
création d'un nouvelle feature basée sur la branche develop

	$ git flow feature start myFeature  #git checkout -b feature/Myfeature

Qaund la feature est terminé

	$git flow feature finish myFeature 

* on fusionne myFeature avec develop 
* suppression de la branch myFeature
* on se place sur la branch develop	