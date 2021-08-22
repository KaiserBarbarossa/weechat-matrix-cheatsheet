# Kommandos für WeeChat-Matrix

(c) 2021 tuxifreund aka KaiserBarbarossa

**Lizenz:** CC BY-NC-SA 2.5

(https://creativecommons.org/licenses/by-nc-sa/2.5/)

## /matrix

| Unterkommando | Beschreibung | Beispiel |
| -------- | -------- | -------- |
| server add|delete|list|listfull  | Server hinzufügen/entfernen/auflisten | /matrix server add Servername example.org:123 |
| connect | mit Server verbinden | /matrix connect Servername |
| disconnect  | von Server trennen  | /matrix connect Servername  |
| reconnect  | mit Server neuverbinden | /matrix reconnect Servername  |

# /olm

/help olm dürfte hier mehr erleuchtend sein.

# /devices

| Unterkommando | Beschreibung | ggf. Beispiel  |
| --------  |  -------- |  -------- |
| list  | Geräte anzeigen  | /devices list  |
| delete  | Gerät löschen  | /device delete DEVICE-ID  |
| set-name  | Gerät umbenennen  | /device set-name TollerName  |

## Andere Kommandos

| Kommando  | Beschreibung  | ggf. Beispiel  |
| --------  | --------  | -------- |
| /invite  | jemanden in einen Kanal einladen (im entsprechenden Raum ausführen) | /invite USER-ID  |
| /join  | einen Kanal betreten  | /join #WeeMatrix:matrix.org  |
| /kick  | jemanden aus dem aktuellen Raum kicken  | /kick USER-ID Grund  |
| /me  | wie im IRC ;)  | /me ist auch da  |
| /part  | einen Raum verlassen  | /part (#WeeMatrix:matrix.org)  |
| /topic  | Kanalthema ändern  | /topic Neues Topic / /topic -delete  |
| /upload  | eine Datei hochladen  | /upload DATEI  |
| /send-anyways  | Senden Sie die letzte Nachricht in einem Raum, obwohl es nicht verifizierte Geräte gibt. Die nicht verifizierten Geräte werden nach Ausführung dieses Befehls als ignoriert markiert.  |   |
| /reply-matrix  | Auf eine Nachricht antworten  | s. /help reply-matrix  (**[Funktioniert im Moment nicht](https://github.com/poljar/weechat-matrix/issues/233)**)|
