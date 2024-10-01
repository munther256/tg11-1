# Einfuerung
## Github einrichten
1. github account mit der Schul-Email Adresse angelegt.
2. Repository `Tg11-1` mit `readme.md`anlegen.
3. einen neuen ordnermit Stunden Nummer anlegen. Bsp. `01 Einfuerung`
4. eine neue Datei `ErstesDokument.md` anlegen.

## Erstes Markdom Befehle 
### Überschriften
1. Eine Überschrift wird mit `# Überschrift` erzeugt.
Die nächste Ebene wird mit `## Überschrift 2 `, `### Überschrift 3` usw. erzeugt. 

## Arbeitsablauf in Github 
1. Einen neue **Datei/Ordner** erstellen.
2. die Quellcodeverwaltung aufrufen.
3. Alle geänderten Dateien **stagen**. Alternativ kann in Terminal der Befehl `git add *-*` eingegeben werden.
D.h. Alle Dateien werden ab jetzt im lokalen Repository (nicht auf Github) verwalten. 
4. einen aussagekräftigen Test in das Feld über den `commit`- Button eingeben und die schaltfläche commit drücken. Der Befehl in Terminal lautet 
´
```bash
git commit -m Erstes File erstellt
```

5. Synchronisieren anklicken um die Dateien auf das **Remote-Repository** auf **Github** hochzuladen. Der Terminal Befehl lautet:

```bash
gilt push -u main `https://github.com/<username>/<reponame>.git`
git push -u origin main
```
