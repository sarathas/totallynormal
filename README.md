# totallynormal

Hier gibts Dinge f�r streng geheime Sachen.

Kleiner git-Workshop:

1. git runterladen [https://git-scm.com/downloads]

2. git installieren

3. Git Bash in beliebigem Verzeichnis �ffnen

Sehr wichtige Befehle:

	git clone <Repo>
	
erstellt lokale Kopie eines entfernten Repos (z.B: von diesem hier. Oben links bei "Clone or Download" kopiere man sich die Adresse).

	git status
	
zeigt an, in welchem Zustand sich das Repo im Vergleich zum letzten Stand befindet. Haben sich Dateien lokal oder im entfernten Repo ge�ndert? Hier wird das angezeigt.

	git pull
	
l�dt sich den aktuellen Stand des entfernten Repos.

�ndern von Dateien machen wir mal sp�ter ;)	

gpx ist ein bin�res Format, das hei�t dass sich alle Nase lang was daran �ndern kann. Sollte `git pull` mal nciht funktioneren, weil tretlise.gpx sich lokal
 ge�ndert hat, dann kann man das beheben mittels 
 
	git checkout -- tretlise.gpx
	
(oder welche Datei auch immer).
	
