# totallynormal

Hier gibts Dinge für streng geheime Sachen.

Kleiner git-Workshop:

1. git runterladen [https://git-scm.com/downloads]

2. git installieren

3. Git Bash in beliebigem Verzeichnis öffnen

Sehr wichtige Befehle:

	git clone <Repo>
	
erstellt lokale Kopie eines entfernten Repos (z.B: von diesem hier. Oben links bei "Clone or Download" kopiere man sich die Adresse).

	git status
	
zeigt an, in welchem Zustand sich das Repo im Vergleich zum letzten Stand befindet. Haben sich Dateien lokal oder im entfernten Repo geändert? Hier wird das angezeigt.

	git pull
	
lädt sich den aktuellen Stand des entfernten Repos.

Ändern von Dateien machen wir mal später ;)	

gpx ist ein binäres Format, das heißt dass sich alle Nase lang was daran ändern kann. Sollte `git pull` mal nciht funktioneren, weil tretlise.gpx sich lokal
 geändert hat, dann kann man das beheben mittels 
 
	git checkout -- tretlise.gpx
	
(oder welche Datei auch immer).
	
