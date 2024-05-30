## Anleitung - Skript zur Verwaltung von Rocket League Videos

**Hinweis**: Diese .exe ist ein Add-On für BakkesMods "Bakelite", das seit Jahren nicht mehr aktualisiert wurde. Bakelite muss immer noch installiert sein, um dieses Skript verwenden zu können. [Hier ist der Link zu Bakelite](https://bakkesplugins.com/plugins/view/256). (Der Bakelite-Code wurde nicht für dieses Skript verwendet)

Nach der Installation von Bakelite öffnen Sie Rocket League und navigieren Sie zu den Plugin-Einstellungen von Bakelite. Aktivieren Sie "Aufnahmen aktivieren" und lassen Sie die restlichen Einstellungen deaktiviert.

Vergessen Sie nicht, die Highlights in NVIDIA GeForce Experience mit ALT + Z zu aktivieren.

Dieses Skript wurde entwickelt, um die Verwaltung von Rocket League Videos zu optimieren. Es erleichtert das Umbenennen, Verschieben und Löschen von Videos aus bestimmten Ordnern.

### Anleitung zur Verwendung

1. **Interaktion**:
   - Befolgen Sie die während der Ausführung des Skripts angezeigten Anweisungen.
   - Wählen Sie, ob Videos markiert, wiederholt, verschoben oder gelöscht werden sollen.

2. **Abschluss**:
   - Überprüfen Sie am Ende des Skripts die Statistiken, um zu sehen, welche Aktionen durchgeführt wurden.

### Einrichten der automatischen Ausführung

Um sicherzustellen, dass das Skript bei jedem Systemstart automatisch ausgeführt wird, befolgen Sie diese Schritte:

1. **Öffnen Sie das Ausführen-Fenster**:
   - Drücken Sie die Windows + R-Tasten, um das Ausführen-Fenster zu öffnen.

2. **Navigieren Sie zum Startordner**:
   - Geben Sie `shell:startup` in das Ausführen-Fenster ein und drücken Sie die Eingabetaste. Dadurch wird der Startordner geöffnet.

3. **Fügen Sie eine Verknüpfung hinzu**:
   - Verschieben Sie die Verknüpfung des Skripts, die auf dem Desktop erstellt wurde (`AutomaticMp4Drager`) in den geöffneten Startordner.

4. **Starten Sie den Computer neu**:
   - Starten Sie Ihren Computer neu, um sicherzustellen, dass das Skript bei jedem Start automatisch ausgeführt wird.

### Unterstützte Videoplayer

Das Skript verwendet eine vordefinierte Liste von Videoplayern, um laufende Prozesse zu beenden. Stellen Sie sicher, dass diese Liste bei Bedarf aktualisiert wird. Die folgenden Videoplayer sind in das Skript integriert:

- **Video.UI.exe**
- **Microsoft.Media.Player.exe**
- **VLC Media Player**: `vlc.exe`
- **Windows Media Player**: `wmplayer.exe`
- **Media Player Classic**: `mpc-hc.exe`
- **PotPlayer**: `PotPlayerMini64.exe`
- **Kodi**: `kodi.exe`
- **Plex Media Player**: `PlexMediaPlayer.exe`
- **SMPlayer**: `smplayer.exe`
- **MPV**: `mpv.exe`
- **GOM Player**: `GOM.exe`
- **DivX Player**: `DivXPlayer.exe`

Stellen Sie sicher, dass diese Liste gemäß Ihren Anforderungen verwendet wird, um sicherzustellen, dass alle relevanten Videoplayer-Prozesse vor Aktionen wie dem Verschieben oder Löschen von Dateien beendet werden. Das Skript verlässt sich auf diese Liste, um laufende Videoplayer-Prozesse zu identifizieren und zu stoppen.

### Erstellte Ordner

Bei der Ausführung dieses Skripts werden die folgenden Ordner erstellt:

- **RLTrashCan**: Dieser Ordner wird auf dem Desktop erstellt und dient als Papierkorb für Rocket League-Videos.
- **RLMoveTo**: Dieser Ordner wird im Videoordner des Benutzers erstellt und dient als temporärer Speicher für Rocket League-Videos, bevor sie markiert oder gelöscht werden.
- **RocketLeagueClips**: Dieser Ordner wird im Videoordner des Benutzers erstellt und dient als Zielordner für markierte Rocket League-Videos.

### Hinweise

- **Vorsicht beim Löschen von Dateien**:
  - Seien Sie vorsichtig beim Löschen von Dateien, da dieser Vorgang nicht rückgängig gemacht werden kann.

### Deinstallation des Programms

- **Deinstallation**:
  - \Program Files\RLVideoManager\Uninstall.exe oder Öffnen Sie die Systemsteuerung, Programme, Programm deinstallieren, RLVideoManager

- **Anforderungen**:
  - [BakeLite](https://bakkesplugins.com/plugins/view/256)
  - [Geforce Experience](https://www.nvidia.com/de-de/geforce/geforce-experience/)

### Mögliche Virenentdeckung

- **Nicht signierte Anwendung**:
  - Die .exe-Datei kann als Virus erkannt werden, da es sich um eine nicht signierte Anwendung handelt. Seien Sie versichert, dass dies ein falsch positiver Alarm ist.

### Lizenz

Dieses Skript wird unter einer MIT-Lizenz bereitgestellt.

### Autoren

Dieses Skript wurde von [FuZeee](https://github.com/FuZeee) erstellt.

### Versionshistorie

- Version 1.0: Erstveröffentlichung des Skripts.

### Unterstützung

Für Probleme oder Fragen wenden Sie sich bitte über den [GitHub-Link](https://github.com/FuZeee/RLVideoManager/issues).

Vielen Dank, dass Sie dieses Skript verwenden!
