![Banner](banner.png)

# Was ist Neptune?
Neptune ist eine Version Indepent Spigot Framework welche es dir ermöglicht ohne mit Reflections oder NMS ein Spigot Plugin für jede Version ab der 1.12 zu entwicklen.

# Wieso sollte man Neptune verwenden?
Jeder Plugin Developer kennt das Problem - Ihr wollt ganz normal ein Plugin für euren Server entwickeln und z.B. ein NPC Spawnen. Nun steht ihr vor einer riesen Aufgabe. Man muss mit Reflections und Datawachter Manipulation Arbeiten um mit 100 Zeilen Code ein einzigen NPC zu erstellen.

Auch Hologramme zu erstellen kann für viele, vorallem für Entwickler die gerade er mit der Spigot API angefangen haben ein großes grauen sein.

Das soll Neptune verhindern! Neptune bietet eine vielzahl von Methode mit denen man NPCs, Hologramme oder auch Scoreboards ganz einfach erstellen kann.

# Wie löst Neptune diese Probleme?
Neptune besteht zum einen aus einer Interface basierenden API und verschiedenen Spigot Plugins die auf eine gewisse Version abgestimmt sind die diese Interfaces implementieren und den dummy Methoden ihre Funktion geben.

# Wie nutze ich Neptune?
Du musst lediglich die API via Maven oder Gradle in dein Projekt einbinden und drauf los coden.
Eine genau Anleitung zu Neptune findest du in der Wiki.

Jetzt musst du nur noch das Neptune Plugin für deine Spigot Version und dein Entwickeltes Spigot Plugin in dein plugins ordner packen und dein Server neu starten.

Wenn du keine Fehler beim programmieren gemacht hast sollten beide Plugins problemlos starten.

Wenn du dein Server jetzt auf eine neue Version updaten willst, musst du lediglich die Neptune Plugin Jar ersetzen.

# API 

## Maven
```xml
<repository>
  <id>nachgecodet</id>
  <url>https://repo.nachgecodet.de/releases/</url>
</repository>

<dependency>
  <groupId>de.nachgecodet.neptune</groupId>
  <artifactId>api</artifactId>
  <version>LATEST</version>
</dependency>
```
