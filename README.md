# Smart-Mirror_Codes-Befehle
Hier findet ihr alle Befehle und auch den fertigen Code meiner Smart Mirror Youtube-Teile

## Smart Mirror mit dem Raspberry Pi - Teil 1 (Hardware)

https://www.youtube.com/watch?v=iquC3QyNJUg

## Smart Mirror mit dem Raspberry Pi - Teil 2 (Software)

### Bildschirm drehen
Wenn ihr den Spiegel bzw. den Bildschirm lieber in Hochformat verwenden möchtet, könnt diesen mit folgeden B drehen.
Konfigurationsdatei öffnen:
```c
sudo nano /boot/config.txt
```

```c
display_rotate=0  //Normal
display_rotate=1  //90 Grad
display_rotate=2  //180 Grad
display_rotate=3  //270 Grad
```

### Konfigurationsdatei öffen
Die MagicMirro Konfigurationsdatei findet ihr im Ordner config.

config Ordner:
```c
cd MagicMirror/config
```
config.js öffnen
```c
sudo nano config.js
```

### Dateien Speichern & Schließen
Wenn ihr Dateien in der Konsole speichern oder schließen wollte, könnt ihr das mit folgenden Befehlen.

Datei speichern:
**Strg+O**

Datei schleißen:
**Strg+X**

## Smart Mirror mit dem Raspberry Pi - Teil 3 (Module)
